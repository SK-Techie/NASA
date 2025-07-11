pipeline {

    agent any

    stages {
        stage('clone code') {
            steps {
            echo "clone the code"
            git branch: 'main', credentialsId: 'Shubham_Kelhe', url: 'https://github.com/SK-Techie/NASA.git'
            }
        }
    }
}