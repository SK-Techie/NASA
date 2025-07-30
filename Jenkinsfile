pipeline {

    agent any

    stages {
        stage('clone code') {
            steps {
            echo "clone the code"
            git credentialsId: 'github-token', url: 'https://github.com/SK-Techie/NASA.git'
            }
        }
    }
}
