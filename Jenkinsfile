pipeline{
	agent any
	stages {
        stage('build') {
            steps {
		sh 'python3 --version'
		sh 'python3 -m pip freeze -r ./requirements.txt'
            }
        }
    }
}
