pipeline {
    agent any
    stages {
        stage ('BUILD') {
            steps {
                 echo "its build stage "
                  }
        }
        stage ('DEPLOY') {
            steps {
                #!/bin/bash
                sh '''
                echo "its deploy stage"
                sleep 5
                pwd
                ls
                '''
            }
        }    
            
        
    
    }
}       
