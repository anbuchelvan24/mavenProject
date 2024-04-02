pipeline {
    agent any
    
    stages {
        stage('Display Project Directory') {
            steps {
                // Display project directory
                script {
                    def projectDirectory = pwd()
                    echo "Project directory: ${projectDirectory}"
                }
            }
        }
    }
}

