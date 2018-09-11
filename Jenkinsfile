pipeline {
    agent {label 'centosforeman'}
    stages {
        stage('Create a host of Centos server 7') {
            steps {
                sh '/home/jenkins/stage1.sh'
            }
        }
        stage('Operating system is about to be installed') {
            steps {
                sh '/home/jenkins/stage2.sh'
            }
        }
        stage('Check if VM is ready and attached with IP') {
            steps {
                sh '/home/jenkins/stage5.sh'
            }
        }
   }
}
