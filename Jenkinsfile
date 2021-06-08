pipeline{
   agent any
   stages{
       stage("Git Checkout")
           steps{
               git credentialsId: '22be3db6-cd45-410f-b8d8-8e5c0fe6de3b', url: 'https://github.com/dvkrish5/teamchange.git'
              }  
        stage("Maven Build"){
            steps{
                sh "mvn clean package"
                }
             }
          }   
       }         
