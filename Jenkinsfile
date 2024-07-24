pipeline {
  agent any
  stages {
    
   stage(' Environment variables') {

     steps{
       sh "printenv"

  }
}
    stage('Print Branch name') {
      steps {
        echo  $GIT_BRANCH
      }
    }
}
}
