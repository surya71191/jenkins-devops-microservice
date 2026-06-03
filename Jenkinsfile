pipeline {
	//agent any
	//agent { docker { image 'maven:3.6.3'}}
	agent { docker { image 'node:13.8'}}
	stages {
		stage('Build'){
			steps{
				sh "node --version"
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
		stage('Package the application'){
			steps{
				echo "Package the application"
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
		failure{
			echo "I execute when failed"
		}
	}
}