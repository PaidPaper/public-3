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
                echo 'RED'
                sleep(5)
                echo 'YELLOW'
                sleep(10)
                echo 'GREEN'
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
