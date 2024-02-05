pipeline{
a  gent any 
  stages{
    stage('Build'){
        steps{
          echo 'Hi! My name is Ahmed'
          sh './gradlew.build --no-daemon'
          archiveArrifacts artifacts: 'dist/trainSchedule.zip'
        }
    }
  }
}
