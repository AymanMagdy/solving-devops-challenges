
pipeline {
    agent any

    stages {
        stage('Run the containers..') {
            steps {
                sh "docker-compose -f /home/aymansoliman/Desktop/AymanData/Work/ITI/Intake\ 40/solving-devops-challenges/docker-compose.yml up "
            }
        }
        stage('Testing stage') {
            steps {
                echo 'Here will be the unit testing stage..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Here will deploy to AWS.'
            }   
        }
    }
}
