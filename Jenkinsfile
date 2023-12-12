pipeline {   
    agent any

    stages {   
        stage('hotfix branch updated') { 
            steps { 
               sh 'echo "This is hotfix branch updated"' 
            }
        }
     
        stage('test') { 
            steps { 
               sh 'echo "test application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
