pipeline {
  agent {
    node {
      label 'ubuntu'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'mvn install'
      }
    }
  }
}