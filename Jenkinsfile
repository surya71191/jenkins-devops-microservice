pipeline {
	//agent any
	//agent { docker { image 'maven:3.6.3'}}
	agent { docker { image 'nodejs:13.8'}}
	stages {
		stage('Build'){
			steps{
				sh "mvn --version"
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
		failure{
			echo "I execute when failed"
		}
	}
}