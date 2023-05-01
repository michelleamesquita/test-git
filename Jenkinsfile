pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh ' sh \'python3 -v\''
      }
    }

    stage('test') {
      steps {
        sh '''git branch \'main\', url \'https://github.com/michelleamesquita/test-git.git\'
sh \'python3 hello.py\''''
      }
    }

    stage('deploy') {
      steps {
        sh 'echo \'finished :D\''
      }
    }

  }
  environment {
    build = 'build'
  }
}