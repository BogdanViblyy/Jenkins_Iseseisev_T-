pipeline {
    agent any

    stages {
        stage('Установка зависимостей') {
            steps {
                sh 'npm install'
            }
        }
        stage('Запуск приложения') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
