pipeline {
    agent any

    stages {
        stage('update upgrade') {
            steps {
                echo 'mise à jour et mise à niveau'
                sh 'apt update'
                sh 'apt upgrade'
            }
        }
    }
}
