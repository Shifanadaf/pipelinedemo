pipeline {
    agent any
    stages {
        stage('Breakfast') {
            steps {
                echo 'I am having breakfast'
            }
        }
        stage('Workout') {
            steps {
                echo 'I am working out'
            }
        }
        stage('Study') {
            steps {
                echo 'I am studying'
            }
        }
        stage('Family Time') {
            steps {
                echo 'I am spending time with family'
            }
        }
        stage('Play') {
            steps {
                echo 'I am playing'
            }
        }
    }
    post {
        success {
            echo 'My day went well'
        }
        failure {
            echo 'Something went wrong during the day.'
        }
    }
}
