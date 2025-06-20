pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                nvm( "20.14.0" ) {
                    sh "npm install"
                    sh 'npm run build'
                }
            }
        }
    }
}
