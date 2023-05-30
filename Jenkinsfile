pipeline {
    agent any
    stages{
        stage('Initialize'){
            steps{
                echo "Iniciando pipeline"
            }
        }
        stage('Build') {
            steps {
                sh 'mvn -B package'
            }
        }

    }
}