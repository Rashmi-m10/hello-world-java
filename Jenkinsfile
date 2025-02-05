pipeline {
    agent any

    stages {
        
        stage('Build') {
            steps {
               bat 'javac src/test/java/com/helloworld/MyCalculatorTest.java'
            }
        }
        stage('Run') {
            steps {
               bat 'java src/test/java/com/helloworld/MyCalculatorTest'
            }
        }
    }
}
