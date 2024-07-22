pipeline {
    agent any
    stages {
        stage('Prepare') {
            steps {
                // Ensure the script has execute permissions
                sh 'chmod +x ./hello2.sh'
            }
        }
        stage('Run Hello World Script') {
            steps {
                sh './hello2.sh'
            }
        }
    }
}
