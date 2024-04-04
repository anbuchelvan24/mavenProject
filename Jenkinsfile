pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
        stage('Run') {
            steps {
                sh 'java -jar /path/to/your/project.jar'
            }
        }
    }
}
