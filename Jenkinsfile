pipeline {
    agent any

    stages {
        
        stage('Build') {
            steps {
               bat 'javac MyCalculatorTest.java'
            }
        }
        stage('Run') {
            steps {
               bat 'java MyCalculatorTest'
            }
        }
    }
}
