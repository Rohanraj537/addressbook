pipeline {
 agent any
 stages {
  stage ('compile the application') {
   steps {
    sh 'mvn compile'
   }
  }
  stage ('Test code') {
   steps {
    sh 'mvn test'
   }
  }
   }
}
