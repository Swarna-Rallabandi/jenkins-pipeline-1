pipeline {
    agent {
        label 'java-slave4'
    }
    stages {
     stage ('build')
        steps {
            echo " this is a build stage"
         }
    }
     stage ('groovycodestage'){
        steps {
            script {
                def cource = 'k8s'
                if (course == 'k8s')
                println('thanks for enroling to k8s course')
                else
                println('do enroll to k8s')
            }
        }
    }

}
