pipeline {
        agent any
        tools {
         maven 'maven3.5'       
        }
        stages {
             stage("build") {
             steps {
             echo "welcome to the build stage"
               sh "mvn install"
              }
          }
         stage("test") {
          steps {
          echo "Welcome to the test stage"
          }
      }
      stage("Deploy") {
         steps {
         echo "Welcome to the Deploy stage"
    
            }
       }      
          
    }
 }
 
   
      
          
          
