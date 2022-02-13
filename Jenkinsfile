
pipeline{
	agent any

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
