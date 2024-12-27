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
                bat './list_files.sh'
            }
        }
    }
}
