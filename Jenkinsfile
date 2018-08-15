pipeline {
  agent any
  stages {
    stage('stage0') {
      steps {
        echo 'jjj'
        jiraComment(issueKey: 'JJT-4', body: 'klk;fsfdsfdsf')
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
      }
    }
  }
}