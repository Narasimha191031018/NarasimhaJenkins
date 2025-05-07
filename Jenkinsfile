pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Narasimha191031018/NarasimhaJenkins.git'
            }
        }

        stage('Compile') {
            steps {
                bat 'javac src/*.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java -cp src HelloWorld'
            }
        }
    }
}
