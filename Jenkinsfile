pipeline{
	agent none
	stages {
        stage('build') {
            agent{ docker {image 'python:latest'} }
            steps {
                sh 'python --version'
            }
        }
    }
}
