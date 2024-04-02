pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Example: Check out code from GitHub
                git 'https://github.com/anbuchelvan24/mavenProject.git'
                
                // Example: Build the project using Maven
                sh 'mvn clean install'
                
                // Example: Run unit tests
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                // Example: Deploy the built artifact
                // Add your deployment steps here
            }
        }
    }
}
