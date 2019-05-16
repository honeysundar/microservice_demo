pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'mvn package'
            }
        }
        stage('Test') { 
            steps {
                echo "test in progress"
            }
        }
        stage('Deploy') { 
            steps {
                echo "deployment in progress"
            }
        }
    }
}
