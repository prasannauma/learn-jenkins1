pipeline {
    agent any
         stages {
              stage ('declaring variables in this stage') {
                  steps {
                  script {
                  abc = "hello"
                  xyz = "how r u"
                  drg =  "take care"
                  print "abc = ${abc}"
                  }
                  }
              }
              stage (' access variables from another stage') {
                   steps {
                   script {
                   print "xyz = ${xyz} "
                   }
                   }
              }
               stage (' access variables from another stage') {
                   steps {
                   script {
                   print "drg = ${drg}"
                   }
                   }
               }

         }
}

