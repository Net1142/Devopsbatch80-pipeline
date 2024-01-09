pipeline {
  agent any
  stages {
    stage('Commit') {
      steps {
        echo 'Commit the code'
      }
    }

    stage('Build') {
      steps {
        echo 'Build'
      }
    }

    stage('Test ') {
      parallel {
        stage('Test ') {
          steps {
            echo 'Test Code'
          }
        }

        stage('Stage ') {
          steps {
            echo 'Stage the code'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Deploy the code'
          }
        }

        stage('Operate') {
          steps {
            echo 'Operate'
          }
        }

      }
    }

  }
}