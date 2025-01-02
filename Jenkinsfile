pipeline{
  agent any
  stages{
    stage('Built'){
      steps{
        echo "i am building"
      }
    }
    stage('Test'){
      steps{
        echo "i am testing"
      }
    }
    stage('Deploy'){
      steps{
        echo "deploying"
      }
    }
  }
  post {
    success{
      echo "Your pipeline is success"
    }
    failure {
      echo "Pipeline failed"
    }
  }
}
