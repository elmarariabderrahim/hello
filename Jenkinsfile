pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
               retry(3) {
                   chmod -x './helllo.sh'
                    sh './helllo.sh'
                   
                }
                timeout(time: 3, unit: 'MINUTES') {
                    chmod -x './t_out.sh'
                    sh './t_out.sh'
                }

                
                
            }
        }
    }
}
