pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World ********* '
            }
        }
         when {
                not { branch 'ppp'}
            }
        stage('Example Deploy') {
           
            steps {
                echo 'Deploying'
            }
        }
    }
}
