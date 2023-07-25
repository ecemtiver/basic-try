pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Buraya yapılacak işlemleri ekleyin
                sh 'npm install' // Örnek bir npm kurulumu
            }
        }
        stage('Test') {
            steps {
                // Buraya test aşamalarını ekleyin
                sh 'npm test' // Örnek bir test komutu
            }
        }
        stage('Deploy') {
            steps {
                // Buraya dağıtım aşamalarını ekleyin
                sh 'npm deploy' // Örnek bir deploy komutu
            }
        }
    }
}
