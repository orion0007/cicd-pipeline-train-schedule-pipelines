pipeline 
{
  agent any
  stages 
  {
    stage ('Build') 
    {
      steps 
      {
        echo 'Running build automation'
        sh './gradlew build --nodaemon'
        archiveArtifacts artifacts: 'dist/trainschedule.zip'
      }
     }
    }
  }
