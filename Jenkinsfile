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
                sh 'chmod +x ${WORKSPACE}/hello1.sh'
            }
        }
        stage('Run Hello World Script') {
            steps {
                sh 'env'
                sh 'pwd'
                sh 'ls -al'
                sh 'bash ${WORKSPACE}/hello1.sh'
            }
        }
    }
}
