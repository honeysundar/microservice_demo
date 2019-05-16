pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'mvn compile'
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
