pipeline {
 agent {
  node { label 'workstation' }
 }
 stages {
  stage('one'){
   steps {
    sh'echo one'
   }
  }
  stage('two'){
   steps {
    sh'echo two'
   }
  }
  stage('three'){
   steps {
    sh 'echo three'
   }
  }

 }
 post {
  always {
   echo 'Sending Email'
  }
 }
}