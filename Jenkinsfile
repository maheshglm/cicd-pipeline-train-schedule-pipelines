pipeline{
  agent any 
  
  stages {
  
    stage("Build"){
      steps {
        echo 'RUnning in build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  
  }
  
  
  
  
  
  
  
}
