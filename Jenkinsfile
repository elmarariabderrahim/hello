pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World ********* '
            }
        }
        stage('Example Deploy') {
            when {
               not branch 'ppp'
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}
