pipeline { 
  agent {
    docker {
      image: 'node 12.18.3-alpine'
      args: '-p 8001:8001'
    }
  } 
    stages { 
        stage ('Build') { 
          sh 'npm install'
        }
        stage ('Test') { 
          echo 'Test Stage'
        }
        stage ('QA') { 
          echo 'QA Stage'
        }
        stage ('Deploy') { 
          echo 'Deploy Stage
        }
        stage ('Monitor') { 
          echo 'Monitoring'
        }
 
    }           
 }
