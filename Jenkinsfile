pipeline {
    agent {label 'centosforeman'}
    stages {
        stage('Create a file') {
            steps {
                sh '/bin/hammer host create --name test-vm.ucsbang6.com --hostgroup "Provision from centosforeman.ucsbang6.com" --interface="primary=true, provision=true, managed=true, virtualnic=true, mac=00:50:56:8d:40:81, deviceidentifier=ens162, ip=10.211.203.245" --environment production  --operatingsystem "Centos7.5new" --architecture "x86_64" --domain-id 1  --provision-method build --medium CentOS_7_x86_64 --partition-table "Kickstart default" --ask-root-password no -u admin -p bRQW84EyPjEwH64t'
            }
        }

    }
}
