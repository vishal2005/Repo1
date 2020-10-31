pipeline {
        agent any
        environment {
         NEW_VERSION = '1.3.0'       
        }
        stages {
             stage("build") {
             steps {
             echo "welcome to the build stage"
             echo "building version ${NEW_VERSION}"
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
 
   
      
          
          
