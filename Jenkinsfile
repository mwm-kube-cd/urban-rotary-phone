pipeline {
    agent any
    //agent {
    //    docker {
    //        image 'maven:3-alpine' 
    //        args '-v /root/.m2:/root/.m2' 
    //    }
    //}
    stages {
        stage('Build') { 
            steps {
                sh 'echo hello from Jenkinsfile!' 
                sh 'echo Waiting 30s...'
                sh 'sleep 30'
                sh 'echo done'
            }
        }
    }
}
