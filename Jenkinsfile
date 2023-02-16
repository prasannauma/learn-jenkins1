pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
        stage ('delaring variables at stage level') {
            steps {
                script {
                def abc = "hello"
                def a = 10
                print "abc = {$abc}"
                print  "a = {$a}"
                }
            }
       }
    }
     post {
            always {
                cleanWs()
            }
       }
    }





