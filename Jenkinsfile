pipeline {
    agent { docker { image 'phpweb' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
