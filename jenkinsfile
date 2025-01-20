pipeline {
    tools{
        jdk 'JAVA_HOME'
        maven 'M2_HOME'
    }
    agent any

    
    stages {
        stage('git clone') {
            steps {
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
