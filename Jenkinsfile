pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Etape de build avec Git V2"
                sh 'python3 --version'
            }
        }
        stage('Tests') {
            steps {
                echo "Etape de test"
            }
        }
        stage ('Deploy') {
            steps {
                echo "Etape de déploiement"
            }
        }
    }
}
