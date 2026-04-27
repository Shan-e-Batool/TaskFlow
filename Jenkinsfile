pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Shan-e-Batool/TaskFlow'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building TaskFlow Project'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running tests'
            }
        }
    }
}
