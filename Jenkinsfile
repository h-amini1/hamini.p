pipeline {
  agent any
  
  stages {
    stage('Install Dependencies') {
      steps {
        sh 'sudo apt-get update'
        sh 'sudo apt-get install -y python3-pip'
        sh 'pip3 install -r cloud-custodian/requirements.txt'
      }
    }
  }
}
