pipeline {
    agent any
    stages {
        stage('Build') {
            when { 
                changeset "**/*.js" 
            }
            steps {
                echo "Hello World in change set"
            }
        }
    }
}