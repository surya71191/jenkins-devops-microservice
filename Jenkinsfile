pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
		stage('Package') {
			steps {
				echo "Package"
			}
		}
	}

	post {
		always {
			echo "always"
		}
		success {
			echo "Success"
		}
		failure {
			echo "Fail"
		}
	}
}