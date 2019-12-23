pipeline {
    agent {
        docker {
            image 'node:12.14.0-alpine3.11'
            args '-p 3000:3000'
        }
    }
   
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        
    }
}
