// declarative 
pipeline {
	agent any
	stage{
		stage('build'){
			steps{
				echo "build"
			}
		}
		stage{
			stage('test'){
				steps{
					echo "test"
				}
			}
		stage{
			stage('integration test'){
				steps{
					echo "integration test"
				}
			}
		}
	}
}
}