pipeline {
    agent any
    stages {
        stage('Build Application') {
            steps {
                echo env.BUILD_ID
            }
            post {
                always {
                    echo "Now Archiving the Artifacts...."
                    
                }
            }
        }
        
       
        }
    }

