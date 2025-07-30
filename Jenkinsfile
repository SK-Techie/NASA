pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                echo "Cloning public GitHub repository"
                git url: 'https://github.com/SK-Techie/NASA.git'
            }
        }
    }
}
