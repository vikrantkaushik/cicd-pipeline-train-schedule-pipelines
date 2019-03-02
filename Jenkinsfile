pipeline {
  agent any
  stage {
    stage{'Build'} {
    step {
      echo 'Running Build Automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
    }      
  }
}
