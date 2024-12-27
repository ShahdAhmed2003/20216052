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
                
                bat '"C:\\Program Files\\Git\\bin\\bash.exe" ./list_files.sh'
            }
        }
    }
}
