pipeline {
    agent any

    stages {
        stage('First Stage') {
            steps {
                echo 'Prepare'
                git 'https://github.com/Jaibw/jenkinsdemo.git' 
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
