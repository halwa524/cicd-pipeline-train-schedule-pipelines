pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradel build'
        aechiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
