node {
    stage('Build') {
        checkout scm
        sh 'cat Jenkinsfile'
        echo 'Building main'
    }
    stage('Test') {
        sh 'cat Jenkinsfile'
        echo 'Testing main'
    }
    stage('Deploy') {
        echo 'Deploying main'
    }
}
