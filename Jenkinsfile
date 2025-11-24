pipeline {
    agent {
        label 'java-slave4'
    }
    stages {
        stage ('first stage')
        {
            steps {
                echo "hello"
            }
        }
    }
        stage ('groovycodestage') {
            steps {
                script{
                    def cor="ss"
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

