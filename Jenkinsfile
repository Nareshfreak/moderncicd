pipeline {
  agent any
  stages {
    stage('Verify Branch') {
      steps {
        echo $GIT_BRANCH
      }
    }
   stage(' Environment variables')
     steps{
       sh "printenv"

  }
}
