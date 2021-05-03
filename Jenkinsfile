pipeline {
    agent any
    stages {
        stage('Setup Python Virtual Environment'){
            steps {
                sh '''
                    chmod +x envsetup.sh
                    ./envsetup.sh
                    '''
            }
        }
        stage('Setup service'){
            steps {
                sh '''
                    chmod +x service.sh
                    ./service.sh
                    '''
            }
        }
    }
}