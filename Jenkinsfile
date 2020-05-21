pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo 'Build stage from git code'
            }
        }
        stage('Test'){
            steps {
                echo 'Test stage from git code'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy stage from git code'
            }
        }
    }
}
