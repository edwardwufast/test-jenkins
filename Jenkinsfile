pipeline {
  agent any
  stages {
    stage('stage0') {
      parallel {
        stage('stage0') {
          steps {
            echo 'jjj'
            jiraComment(issueKey: 'JJT-4', body: 'klk;fsfdsfdsf')
          }
        }
        stage('') {
          steps {
            sleep 1
          }
        }
      }
    }
    stage('stage1') {
      steps {
        sh 'echo "hello"'
      }
    }
    stage('error') {
      steps {
        sleep 3
        echo 'll'
      }
    }
  }
}