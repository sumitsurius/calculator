pipeline {
  agent any
  stages {
    stage('Compile') {
      steps{
        sh 'mvn clean compile'
      }
    }
    
    stage('UnitTest') {
      steps{
        sh 'mvn clean test'
mail bcc: '', body: 'Hello jenkins user what you want to achieve?', cc: '', from: '', replyTo: '', subject: 'Mail from Jenkins', to: 'sumit.suri@live.com'
      }
    }
    
    stage('DemoStage') {
      steps{
        sh 'echo  hello'
      }
    }

     stage('Package') {
      steps{
        sh 'mvn clean package'
      }
    }    
  }
}
