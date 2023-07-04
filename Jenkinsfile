pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {

                echo 'Building..'
           javac JenkinsDemo.java
        }
}
        stage('Run') {
            steps {

                echo 'Running..'
           java JenkinsDemo
 
}
        }
        stage('Deploy') {
            steps {

  
                echo 'Deploying....'
           
        }
    }
}
}
