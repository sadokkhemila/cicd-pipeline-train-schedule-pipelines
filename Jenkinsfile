pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
       echo 'Running automation building'
       sh './gradlew build --no-daemon'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
