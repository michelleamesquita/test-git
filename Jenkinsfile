pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo \'hi :D\'
      }
    }

    stage('test') {
      steps {
        sh ' git branch \'main\', url \'https://github.com/michelleamesquita/test-git.git\''
      }
    }

    stage('deploy') {
      steps {
        sh 'echo \'finished :D\''
      }
    }

  }
}
