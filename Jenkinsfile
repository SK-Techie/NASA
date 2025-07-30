pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                echo "Cloning public GitHub repository"
                git branch: 'main', url: 'https://github.com/SK-Techie/NASA.git'
            }
        }

        // Add other stages here
    }
}
