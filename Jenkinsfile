pipeline {
    agent none
    stages {
        stage('Build') {
            agent any
            steps {
                echo "Build Stage"
            }
        }
        stage('Test on Linux') {
            agent {
                label 'linux'
            }
            steps {
                echo "Testing script on linux"
            }
        }
        stage('Test on windows') {
            agent {
                label 'windows'
            }
            steps {
                echo "Testing script on windows"
            }
        }
    }
}
