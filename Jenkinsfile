pipeline {
    agent { docker { image 'maven:3.3.3' } }
    
    stages {
        stage('Build') {
            steps {
		echo "sreejith"
                sh 'mvn --version'
            }
        }
    }
}
