pipeline {
	agent any
	stages {
		stage('docker build') {
			steps { sh 'docker -v' }
			steps { sh 'docker images' }
		}
	}
}
