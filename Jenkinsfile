pipeline{
  agent any
  
  stages{
  stage('npm install'){
      steps{
        bat "npm install"
      }
    }
  stage('Build'){
      steps{
        bat "ng s"
      }
    }
  }
}
