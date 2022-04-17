pipeline {
    agent { slave { image 'phpweb' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
