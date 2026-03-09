pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git
'https://github.com/SampathChowdary-hub/
/DevOps-Practice-1.git'
            }
        }
        
        stage('Run Python App') {
            steps {
                bat 'python app.py'
            }
        }
    }
}