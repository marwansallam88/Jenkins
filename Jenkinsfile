pipeline{
	agent any
	stages{
		stage('Compiling'){
			steps{
				echo 'compiling'
			}
		}
		stage('Launching'){
			steps{
				echo 'launching'
			}
		}
		stage('Running'){
			steps{
				echo 'running'
			}
		}
		stage('Running local file'){
			steps{
				bat 'python C:/Users/marwan/Documents/Siemens/JB/sample.py'
			}
		}
	}
}
