pipeline {
    agent any
    
    stages {
        stage('Display Commit History') {
            steps {
                // Checkout the repository
                git url: 'https://github.com/anbuchelvan24/mavenProject.git', branch: 'master'
                
                // Display commit history
                sh 'git log --oneline'
            }
        }
    }
}
