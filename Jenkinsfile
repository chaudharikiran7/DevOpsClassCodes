pipeline {
    agent{node{ label ‘slave’}}
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
