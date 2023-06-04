pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                sh 'ls -lrt ; rm -rf * '
                sh 'git clone https://github.com/nabghour/fsdevops.git'
            }
        }
        stage('Job1') {
            steps {
                sh 'bash fsdevops/essai.sh Job1'
            }
        }
    stage('Job2') {
            steps {
                sleep 30
                sh 'bash fsdevops/essai.sh Job2'
            }
        }
    stage('job3') {
            steps {
                sh 'bash fsdevops/essai.sh Job3'
            }
        }    
        
        
        
        
    }
}
