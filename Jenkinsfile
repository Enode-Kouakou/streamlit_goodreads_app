pipeline{
	agent any
	stages {
        stage('build') {
            steps {
		sh './var/jenkins_home/Python310/python.exe ./book.py/'
            }
        }
    }
}
