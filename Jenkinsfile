pipeline{
	agent none
	stages {
        stage('build') {
            agent{ docker {image 'python:3.10.11'} }
            steps {
                sh 'python --version'
            }
        }
    }
}
