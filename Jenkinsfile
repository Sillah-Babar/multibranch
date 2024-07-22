pipeline {
    agent any

    stages {
        stage('Declarative: Checkout SCM') {
            steps {
                checkout scm
            }
        }
        stage('Prepare') {
            steps {
                sh 'chmod +x ${WORKSPACE}/hello2.sh'
            }
        }
        stage('Run Hello World Script') {
            steps {
                sh 'env'
                sh 'pwd'
                sh 'ls -al'
                sh 'bash ${WORKSPACE}/hello2.sh'
            }
        }
    }
}
