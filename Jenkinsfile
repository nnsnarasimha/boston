pipeline {
    agent any

    stages {
        stage('Git Pull') {
            steps {
                git 'h//github.com/nnsnarasimha/boston.git'
            }
        }
        stage {
            steps { 'build'}
            
        }
        stage('Dev Env') {
            steps {
                git 'https://github.com/nnsnarasimha/boston.git'
            }
        }
        stage('QA Pull') {
            steps {
                git 'https://github.com/nnsnarasimha/boston.git'
            }
        }
    }
}
