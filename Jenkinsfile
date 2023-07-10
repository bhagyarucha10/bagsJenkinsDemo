pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package' // Replace with your build command or script
            }
        }
        stage('Archive') {
            steps {
                archiveArtifacts 'target/*.jar' // Replace with the path to your generated JAR file
            }
        }
    }
}
