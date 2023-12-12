pipeline {   
    agent any

    stages {   
        stage('hotfix branch') { 
            steps { 
               sh 'echo "This is hotfix branch"' 
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
