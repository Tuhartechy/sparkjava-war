pipeline {                                              // 1 // Defines the start of the Jenkins pipeline block
    agent any                                           // 1 // Specifies the pipeline can run on any available agent
    environment {                                       // 2 // Defines environment variables for the pipeline
        PATH = "/opt/maven/bin:$PATH"                   // 2 // Adds Maven's path to the system's PATH variable
    }                                                   // 2 // Ends the environment block
    stages {                                            // 3 // Defines the stages block where multiple stages are declared                     
        stage('build') {                          
            steps {                                    
                sh 'mvn clean install'                  
            }                                        
        }                                            
    }                                                   
}                                                       

