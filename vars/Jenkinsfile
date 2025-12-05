pipeline {
  agent any
  stages {
    stage("dev"){
      when {
        branch "develop"
      }
      steps {
        echo "this is develop branch"
      }
    }
    stage("prod"){
      when {
        branch "main"
      }
      steps{
        echo "this is main branch"
      }
    }
  }
}
