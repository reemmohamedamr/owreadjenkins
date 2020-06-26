pipeline {
  agent any 
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World 2"'
      }
    }
  }
  stages {
    stage('Lint HTML') {
      steps {
        sh 'tidy -q -e *.html'
      }
    }
  }
}