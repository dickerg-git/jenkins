pipeline {

    agent any

    stages {

        stage('Info') {
            steps {
                echo 'Info stage.'
                sh 'pwd'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage.'
                // git "https://github.com/dickerg-git/raspberry"
                // sh "g++ RGDthread.cpp -lpthread -o ARMTest"
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage.'
                sh "../Threads/ARMTest"
            }
        }

    } // end of stages list

} // end of the pipeline file
