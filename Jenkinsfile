pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'step1'
          }
        }

        stage('stage1.1') {
          steps {
            echo 'step2'
          }
        }

      }
    }

    stage('stage2') {
      steps {
        echo 'step2 s '
      }
    }

  }
}