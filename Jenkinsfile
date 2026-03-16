pipeline{
  agent any
  stages{
    stage('Clone'){
      steps{
        git url : 'https://github.com/akashks05/jenkins-demo.git',
          branch:'main'
      }
    }

    stage('Run Python Script'){
      steps{
        sh 'python3 script.py'
      }
    }
  }
}
