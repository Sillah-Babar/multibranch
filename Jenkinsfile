pipeline {
    agent any
    stages {
        stage('Prepare') {
            steps {
                // Ensure the script has execute permissions
                sh 'chmod +x ./hello1.sh'
            }
        }
        stage('Run Hello World Script') {
            steps {
                sh './hello1.sh'
            }
        }
    }
}
