pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
      echo 'Starting Build'
       sh './gradlew build --no-daemon'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
