pipeline {
	agent any
	stages {
		stage('Build'){
			steps{
				echo "Build"
			}
		}
		stage('Test'){
			steps{
				echo "Test"
			}
		}
		stage('Integration Test'){
			steps{
				echo "Integration Test"
			}
		}
	}
	post{
		always{
			echo "I execute always"
		}
		success{
			echo "I execute when success"
		}
		fail{
			echo "I execute when failed"
		}
	}
}