pipeline {   
    agent any

    stages {   
        stage('master branch update') { 
            steps { 
               sh 'echo "This is master branch update"' 
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
