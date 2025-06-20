pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                nvm( "20.14.0" ) {
                    sh "npm install"
                    sh 'npm run build'
                }
                echo 'Building the project...'
            }
        }
    }
}
