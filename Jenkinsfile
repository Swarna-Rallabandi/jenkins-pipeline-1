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
        stage ('new stage') {
            steps {
                echo "welcome to pipelines"
    }
}
    }
}
