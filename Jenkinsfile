node {
    stage('Clone') {
        git branch: 'feature-one', url: 'https://github.com/acheriat/jenkins-java.git'
        echo 'Coloning eature-one Branch ....'
    }
    stage('Build') {
        sh 'javac Main.java'
        echo 'Building eature-one Branch ... (Java class)'
    }
    stage('Run') {
        sh 'java Main'
        echo 'Runing eature-one Branch ... (Java Main)'
    }
}
