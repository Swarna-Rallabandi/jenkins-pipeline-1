
sleep 20pipeline {
    agent {
        label 'java-slave4'
    }
    stages {
        stage ('first stage')
        {
            steps {
                echo "hello"
                
               // sleep 20
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
