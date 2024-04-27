pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/nguyenthanhdat23012003/CRUD-Microservice-Docker.git'
            }
        } 
        // stage('Run') {
        //     steps {
        //         sh 'docker compose build; docker compose up'  
        //     }
        // }
        // stage('Test') {
        //     steps {
        //         sh 'curl -4 http://localhost:80/java/all > test.txt'
        //     }
        // }
    }
}