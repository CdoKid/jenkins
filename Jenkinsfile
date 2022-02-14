pipeline {
    agent {
	label "Docker"
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
