pipeline {
  agent {
    node {
      label 'Suni'
    }

  }
  stages {
    stage('build') {
      agent {
        node {
          label 'Suni'
        }

      }
      steps {
        echo 'hello world'
      }
    }
    stage('test') {
      steps {
        echo 'testing'
      }
    }
  }
}