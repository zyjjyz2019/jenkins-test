node {
    stage('Build') {
        sh 'cat Jenkinsfile'
        echo 'Building dev'
    }
    stage('Test') {
        checkout scm
        sh 'cat Jenkinsfile'
        echo 'Testing dev'
    }
    stage('Deploy') {
        echo 'Deploying dev'
    }
}
