pipeline {
    agent {
        node {
            label 'maven'
        }
    }
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/devbyrahami/devops-project-2.git'
            }
        }
    }
}