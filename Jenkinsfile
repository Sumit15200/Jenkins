pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Compiling'
                sh 'javac JavaApp.java'
            }
        }
        
        stage('Run') {
            steps {
                echo 'Runing Application'
                sh "java JavaApp"
            }
        }
   
           
    }
}