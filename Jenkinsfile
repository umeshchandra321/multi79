pipeline {   
    agent any

    stages {   
        stage('updated file') { 
            steps { 
               sh 'echo "This is updated branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
