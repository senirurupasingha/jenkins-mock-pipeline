pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build - Compiling and packaging code using Mavennnnnn'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests - Running tests using JUnit and Selenium'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis - Analysing code quality using Checkstyle'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan - Scanning for vulnerabilities using OWASP Dependency-Check'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging - Deploying to AWS EC2 staging instance'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging - Running integration tests on staging using Selenium'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production - Deploying to AWS EC2 production instance'
            }
        }
    }
}
