pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                retry(3) {
                    sh 'chmod +x helllo.sh'
                    sh './helllo.sh'
                }

                
            }
        }
    }
}
