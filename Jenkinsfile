
pipeline {
    agent any 
    stages {
        stage('Print and list current directory') {
            steps {
                sh 'pwd'
                sh 'ls -al'
            }dddddd
        }
        stage('Show ROS environment variables') {
            steps {
                sh 'env | grep ROS'
            }
        }
    }
}
