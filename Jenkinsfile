pipeline {
  agent any
  stages{
    stage('First Stage'){
      steps{
        sh 'echo print ls'
      }
    }
    stage('Second Stage'){
      steps{
        sh 'echo create touch M'
      }
    }

    stage('Third Stage'){
      steps{
        sh 'sort M'
      }
    }

  }
}
