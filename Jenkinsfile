pipeline {

    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git 'https://github.com/yogesh-kulkarni-DevOps/database-ci-cd.git'
            }
        }

        stage('Run Liquibase Migration') {
            steps {
                bat 'C:\\liquibase-5.0.2\\liquibase update'
            }
        }

    }
}