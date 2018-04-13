pipeline {
   environment {
           DOCKER_HOST='tcp://dlb1.aureacentral.com:2376'
           DOCKER_TLS_VERIFY='1'
           DOCKER_CERT_PATH='/opt/.docker/'
   }
  agent {
       label 'ubuntu1604'
  }
   stages {
       stage("run_test") {
           steps {
              sh "echo starting test this project "
           }
       }          
   }
}
