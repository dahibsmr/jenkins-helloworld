node {
    stage('Clone') {
        git credentialsId: 'b643974d-a209-4a2d-8e0a-b39514bc7112', url: 'https://github.com/dahibsmr/jenkins-helloworld.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
