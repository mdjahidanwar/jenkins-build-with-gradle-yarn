pipeline {
  agent any
  stages{
    stage('build') {
      steps {
        echo 'hello there#########'
        nodejs('nodejs-17.5') {
          sh ' yarn install'
          
        }
      }
    }
    stage('test') {
      steps {
        echo 'hello there-----------'
        withGradle() {
          sh './gradlew -v'
        }
      }
    }

    
  
  
  
  
  }





}
