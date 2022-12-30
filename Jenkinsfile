pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradel build --no-daemon'
        aechiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
