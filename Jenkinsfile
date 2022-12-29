pipeline {
	agent {
		label 'slavenode1'
	}
	stages {
		stage('checkout scm') {
			steps {
				echo "checkout code from scm"
			}
		}
		stage('build') {
			steps {
				echo "mvn clean verify"
			}
		}
	}
}
