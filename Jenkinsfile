pipeline {
    tools{
      
    }
    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/Shradha1907/mvn-jenkins.git'
                echo 'git cloned sucessefully'
            }
        }
        stage('compile') {
            steps {
                sh 'mvn compile'
                echo 'sucessefully build the code'
            }
        }
        stage('unit test') {
            steps {
                sh 'mvn test'
                echo 'sucessefully unit testing done'
            }
        }
        stage('package') {
            steps {
                sh 'mvn package'
                echo 'sucessefully packaged'
            }
        }
        
    }
	}
