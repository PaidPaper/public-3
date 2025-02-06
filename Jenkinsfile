pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sleep(10)
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sleep(5)
                echo 'ready to go!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sleep(10)
            }
        }
    }
}
