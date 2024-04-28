pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/nguyenthanhdat23012003/CRUD-Microservice-Docker'
            }
        } 
       
        stage('Test') {
            steps {
                sh 'echo "fsdfs" > test.txt'
            }
        }
    }
}