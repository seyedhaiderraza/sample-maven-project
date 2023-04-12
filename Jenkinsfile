pipeline {
    agent any 
     tools { 
      maven 'MAVEN_HOME' 
      jdk 'JAVA_HOME' 
    }
    stages {
    stage('maven install') {
      steps {

        sh 'mvn clean install'

      }
    }

  }
}
