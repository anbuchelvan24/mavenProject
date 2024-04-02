pipeline {
    agent any
    
    stages {
        stage('Display File Directory') {
            steps {
                // Checkout the repository
                git url: 'https://github.com/anbuchelvan24/mavenProject.git', branch: 'master'
                
                // Display file directory using ls command
                sh 'ls -R'
                
                // Or you can use the tree command for a more structured view
                // sh 'tree'
            }
        }
    }
}

