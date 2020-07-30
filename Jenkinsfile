pipeline {
  agent any
  stages {
      stage ('build') {
       steps { 
             echo 'Running build automation'
             sh './gradlew build --no-daemon'
             archivesArtifacts artifacts: 'dist/trainshedule1.zip'
         }
       }
    }
}
