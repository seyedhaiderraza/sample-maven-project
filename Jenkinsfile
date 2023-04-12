pipeline {
    agent any 
     tools { 
      maven 'maven' 
    }
    stages {
    stage('maven install') {
      steps {

        sh 'mvn clean install'

      }
    }

  }
}
