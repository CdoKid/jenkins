pipeline {
    agent {
	label "docker"
	}
    environment {
        imageName="sample:latest"
	}

	stages {

		stage('Build') {

			steps {
				sh 'docker build -t $imageName .'
			}
		}
	}
}
