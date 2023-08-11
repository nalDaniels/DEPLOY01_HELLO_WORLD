pipeline {
  agent any

  stages {
    stage ('Build') {
      steps {
        sh "touch build.txt"
     }
   }
    stage ('Test') {
      steps {
        sh "touch test.txt"
      }
    }
     stage ('Deploy') {
      steps {
        sh "echo You did it!"
      }
    }
  }
}
