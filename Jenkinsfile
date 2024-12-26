// pipeline {
//     agent any
//     stages {
//         stage('Breakfast') {
//             steps {
//                 echo 'I am having breakfast'
//             }
//         }
//         stage('Workout') {
//             steps {
//                 echo 'I am working out'
//             }
//         }
//         stage('Study') {
//             steps {
//                 echo 'I am studying'
//             }
//         }
//         stage('Family Time') {
//             steps {
//                 echo 'I am spending time with family'
//             }
//         }
//         stage('Play') {
//             steps {
//                 echo 'I am playing'
//             }
//         }
//     }
//     post {
//         success {
//             echo 'My day went well'
//         }
//         failure {
//             echo 'Something went wrong during the day.'
//         }
//     }
// }


node {
    stage('Build') {
        echo 'I am building'
    }
    stage('Test') {
        echo 'I am testing'
    }
    stage('Deploy') {
        echo 'I am deploying'
    }

    if (currentBuild.result == null) {
        currentBuild.result = 'SUCCESS'
    }

    if (currentBuild.result == 'SUCCESS') {
        echo 'Pipeline completed successfully!'
    } else {
        echo 'Pipeline failed!'
    }
}

