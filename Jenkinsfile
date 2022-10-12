pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Said Running build automation'
        echo 'Life is beautiful'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
