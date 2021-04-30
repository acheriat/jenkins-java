pipeline {
    agent any
    
    stages {
       stage('Clone') {
          git branch: 'main', url: 'https://github.com/acheriat/jenkins-java.git'
          echo 'Coloning Dev Branch ....'
      }    
       stage('Build') {
         sh 'javac Main.java'
         echo 'Building Main Branch ... (Java class)'
       }
       stage('Run') {
          sh 'java Main'
          echo 'Runing Main Branch ... (Java Main)'
       }
   }
}
