pipeline {
    agent {label 'centosforeman'}
    stages {
        stage('Create a host of Centos server 7') {
            steps {
                sh '/home/jenkins/host-foreman-create.sh'
            }
        }
        stage('Waiting for host availability') { 
            steps {
                sh '/home/jenkins/test-ping.sh'
            }
        }
    }
}
