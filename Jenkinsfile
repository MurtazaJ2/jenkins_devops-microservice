// declarative 
pipeline {
	agent any
	stages{
		stage('build'){
			steps{
				echo "build"
			}
		}
		stage('test'){
			steps{
				echo "test"
			}
		}
		stage('integration test'){
			steps{
				echo "integration test"
			}
		}
		stage('webhook test'){
			steps{
				echo "webhook is added"
			}
		}
	} 

	post {
		always {
			echo "I am awesome"
		}
		success {
			echo "I run when you are successful"
		}
		failure {
			echo "i don't run"
		}
	}
}