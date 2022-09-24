pipeline { 
  agent {
    docker {
      image 'node:18-alpine3.15'
      args '-p 8001:8001'
    }
  } 
    stages { 
        stage ('Build') {
          steps {
            sh 'chown -R 112:120 "/.npm"'
            sh 'npm install'
          }  
        }
        stage ('Test') { 
          steps {
            echo 'Test Stage'
          }
        }
        stage ('QA') { 
          steps {
            echo 'QA Stage'
          }
        }
        stage ('Deploy') { 
          steps {
            echo 'Deploy Stage'
          }
        }
        stage ('Monitor') { 
          steps {
            echo 'Monitoring'
          }
        }
    }           
 }
