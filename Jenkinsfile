pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git credentialsId: 'jenkins_slave', url: 'https://github.com/Shradha1907/mvn-jenkins.git'
                echo 'git cloned sucessefully'
            }
        }
        stage('compile') {
            steps {
                echo 'sucessefully compiled'
            }
        }
        stage('package') {
            steps {
                echo 'sucessefully packaged'
            }
        }
        
    }
}
