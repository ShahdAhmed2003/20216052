pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                
                checkout scm
            }
        }
        stage('Run Bash Script') {
            steps {
                // Run the list_files.sh script
                sh './list_files.sh'
            }
        }
    }
}
