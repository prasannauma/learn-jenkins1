pipeline {
    agent any
    stages{
         stage ('declare a varible here') {
              steps {
                   script {
                       def a = "hello"
                       env.b = "how r u"
                       print  "a = ${a}"
                  }
              }
         }
         stage (' accessing a variable') {
              steps {
                   script {
                       env.c = "im good"
                       print "b = ${b}"
                   }
                   script {
                       print "c= ${c}"
                   }
              }
         }
         stage ('if condition') {
             steps {
                 script {
                     if (c == "im good") {
                     print "yes"
                     }
                     else {
                     print "no"
                     }
                 }
             }
         }
    }
}










