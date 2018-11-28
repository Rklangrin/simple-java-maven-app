#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                mvn -DskipTests clean package
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                mvn test
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}