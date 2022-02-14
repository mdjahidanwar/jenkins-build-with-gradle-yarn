pipeline {
  agent any
  stages{
    stage('build') {
      step{
        echo 'hello there#########'
        nodejs('nodejs-17.5') {
          sh ' yarn install'
          
        }
      }
    }
    stage('test') {
      step{
        echo 'hello there-----------'
        withGradle() {
          sh './gradlew -v'
        }
      }
    }

    
  
  
  
  
  }





}
