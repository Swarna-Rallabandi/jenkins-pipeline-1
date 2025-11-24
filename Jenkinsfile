
sleep 20pipeline {
    agent {
        label 'java-slave4'
    }
    stages {
        stage ('first stage')
        {
            steps {
                echo "hello"
                sh 'hostname -i'
                sh 'hostname -i'
                sh 'hostname -i'
                sleep 20
                echo "sleep done "
            }
        }
    
        stage ('groovycodestage') {
            steps {
                script{
                    def cor="ssa"
                    if (cor =='ss') {
                        echo "sssss"
                    }
                    else {
                        echo "false"                
                        
                    }
                }
            }
        }
    }
}
