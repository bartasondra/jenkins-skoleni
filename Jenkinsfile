

pipeline{
  agent any
  
  stages{
    
    stage("test"){
      steps{
        echo env.BRANCH_NAME
      }
    }
  }
  post{
    always{
      echo "im done"
    }
  }
}

