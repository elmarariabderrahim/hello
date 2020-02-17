pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
               retry(3) {
                    sh './helllo.sh'
                }
                timeout(time: 3, unit: 'MINUTES') {
                    sh './t_out.sh'
                }

                
                
            }
        }
    }
}
