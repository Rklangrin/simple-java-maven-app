#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'echo $JAVA_HOME'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'pwd'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'ls'
            }
        }
    }
}