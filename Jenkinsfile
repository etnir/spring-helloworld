pipeline{
     agent any
     tools{
         maven 'maven'
     }
    stages{
        stage("build target"){
            steps{
                script{
                    sh "mvn clean install"
                }
            }
        }
    } 
    
    
}
