pipeline{
  agent any
  stages {
    stage ("build"){
      when {
            branch "master"
        }
      steps {
        echo 'building the app...'
      }
    }
    stage ("test"){
      when {
            branch "master"
        }
      steps {
        echo 'testing the app...'
      }
    }
    stage ("deploy"){
      when {
            branch "master"
        }
      steps {
        echo 'deploying the app...'
      }
    }
  }
}
