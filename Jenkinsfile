node('node'){
        stage('artifacts to s3') {
        try {
               
          withCredentials([[$class: 'AmazonWebServicesCredentialsBinding', accessKeyVariable: 'AWS_ACCESS_KEY_ID', credentialsId: 'deploytos3', secretKeyVariable: 'AWS_SECRET_ACCESS_KEY']]) {
                  sh "aws s3 ls"
                  sh "aws s3 cp pom.xml s3://s3-artifact-machine/"
             }
        }
         catch(err) {
          sh "echo error in sending artifacts to s3"    
           }
        }
}
                
                 
              
                  
                  
 
        
      
          
          
