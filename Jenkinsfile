node {
    stage('clone') {
        git branch: 'main', credentialsId: 'fde57d8b-376f-4bab-a248-2a3d3850575c', url: 'https://github.com/aigleroyale/jenkins-helloword.git'
    }
    stage('build') {
        sh label: '', script:'javac Main.java'
    }
    stage('run') {
        sh label: '', script:'java Main'
    }
}