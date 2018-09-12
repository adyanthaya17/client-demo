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
        stage('Checking if IP has been assigned') {
            steps {
                sh 'cd /home/jenkins/ && ./stage3.sh'
            }
        }
        stage('Check if machine is ready') {
            steps {
                sh '/home/jenkins/stage4.sh'
            }
        }
    }
}
