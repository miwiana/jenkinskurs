pipeline {
    agent any
    stages {
        stage('Step 1st') {
            steps {
                echo 'First pipeline'
            }
        }
        stage('Second stage') {
            steps {
                sh 'cat README.md'
            }
        }
    }
}
