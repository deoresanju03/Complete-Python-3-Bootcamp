pipeline {
  agent any
  stages {
    stage('gitpull') {
      parallel {
        stage('gitpull') {
          steps {
            git(url: 'https://github.com/deoresanju03/Complete-Python-3-Bootcamp.git', branch: 'master')
          }
        }

        stage('') {
          steps {
            sh 'echo "Pull done"'
          }
        }

      }
    }

    stage('shell') {
      steps {
        sh 'done'
      }
    }

    stage('final') {
      steps {
        echo 'final step'
      }
    }

  }
}