node {
    stage('Clone') {
        git branch: 'dev', url: 'https://github.com/acheriat/jenkins-java.git'
        echo 'Coloning Dev Branch ....'
    }
    stage('Build') {
        sh 'javac Main.java'
        echo 'Building Dev Branch ... (Java class)'
    }
    stage('Run') {
        sh 'java Main'
        echo 'Runing Dev Branch ... (Java Main)'
    }
}
