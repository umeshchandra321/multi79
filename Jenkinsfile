pipeline {   
    agent any

    stages {   
        stage('umesh2.0 file') { 
            steps { 
               sh 'echo "This is umesh branch"' 
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
