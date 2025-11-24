pipeline {
    agent {
        label 'java-slave4'
    }
    stages {
        stage ('hostname') {
            steps {
                sh 'hostname -i'
            }
        }
    }
}
