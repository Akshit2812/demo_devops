pipeline{
  agent any{
  stages{
     stage('Testing'){
      steps {
      echo 'running Tests'
      bat python demo_devops.py
      }
     }
     stage('Build'){
     steps{
     echo 'Building jar files...'
     bat mvn 
     }
   }
 }
  }
}
