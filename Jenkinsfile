pipeline {

agent any

stages {

stage('Checkout') {
steps {
git 'https://github.com/yogesh-kulkarni-DevOps/database-ci-cd.git'
}
}

stage('Run Liquibase Migration') {
steps {
sh 'liquibase update'
}
}

}

}