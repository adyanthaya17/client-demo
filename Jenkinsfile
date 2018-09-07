pipeline {
    agent {label 'centosforeman'}
    stages {
        stage('Create a host of Centos server 7') {
            steps {
                sh '/home/jenkins/host-foreman-create.sh'
            }
        }
    }
}
