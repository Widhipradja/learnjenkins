pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Dewa"'
		sh '''
			echo "Multiline shell steps works too"
			ls -lah
		'''
            }
        }
    }
}
