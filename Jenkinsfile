pipeline {
    agent { label 'aws-ec2' }
    stages {
        stage('Clone repository') {
            steps {
                dir('/home/raviteja') {
                git branch: 'main', url: 'https://github.com/CT-RaviTeja66/test55.git'                }
            }
        }       
        stage('Build') {
            steps {
                sh """
                    hostname
                    cd '/home/raviteja'
                    ls
                """
            }
        }
        
        // Add more stages for your pipeline
        // ...
    }
}

