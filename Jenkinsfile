pipeline {
    
    agent any
    
    stages {

        stage('build and push image') {
            steps {
                sh '''
                docker build -t gcr.io/lbg-mea-11/sprint3-saf:v1 .
                docker push gcr.io/lbg-mea-11/sprint3-saf:v1 
               '''
            }
        }
    }
}   
