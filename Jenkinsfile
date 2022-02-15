pipeline {
    agent any
    environment {
        imageName="sample:latest"
	}

	stage('Building image') {
		steps{
		script {
		dockerImage = docker.build imagename
		}
	}
	}
}
