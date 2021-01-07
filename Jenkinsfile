pipeline {
    agent any
    stages {
        stage('Build Application') {
            steps {
                echo env.BUILD_ID
                echo env.BUILD_NUMBER
            }
            post {
                always {
                    echo "Now Archiving the Artifacts...."
                    
                }
            }
        }
        
       
        }
    }

