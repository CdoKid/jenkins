
pipeline{
	agent any

	environment {
        imageName="sample:latest"
	}

	stages {

		stage('Building image') {
		      steps{
			script {
			  dockerImage = docker.build imageName
			}
		      }
		    }
	}
}
