pipeline {
    agent any

    stages {
        stage('First Stage') {
            steps {
                echo 'Prepare'
            }
        }
        
        stage('Second Stage') {
            steps {
                echo 'build and test'
            }
        }
        
        stage('Third Stage') {
            steps {
                sh 'build.sh'
            }
        }
        
        
    }
}
