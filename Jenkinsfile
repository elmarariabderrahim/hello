pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
               retry(3) {
                   sh 'chmod +x helllo.sh'
                    sh './helllo.sh'
                   
                }
                timeout(time: 3, unit: 'MINUTES') {
                    sh'sleep 2m'
                   sh 'chmod +x tout.sh'
                    sh './tout.sh'
                }

                
                
            }
        }
    }
}
