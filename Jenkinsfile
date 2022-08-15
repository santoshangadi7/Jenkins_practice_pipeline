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
                sh '''
                #!/bin/bash
                echo "its deploy stage"
                sleep 10
                pwd
                ls
                '''
            }
        }    
            
        }
    
    }       
