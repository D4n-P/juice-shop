pipeline { 
  agent {
    docker {
      image 'node:12.18.3-alpine'
      args '-p 8001:8001'
    }
  } 
    stages { 
        stage ('Build') {
          steps {
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
