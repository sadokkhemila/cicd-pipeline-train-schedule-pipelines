pipeline {
 agent any
 stages{
   stage('build') {
     stepes {
        echo 'Runnig build automation'
        sh '/.gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainshedule.zip'
     }
   }
 }
}
