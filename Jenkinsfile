pipeline {
    agent any

    stages {
        stage('update & upgrade') {
            steps {
                echo 'mise à jour et mise à niveau'
                sh 'apt update'
            }
        }
        stage('installation de php') {
            steps {
                sh 'apt install git php php-mysql php-xml php-mbstring'
            }
        }
    }
}
