node {
    stage('Build') {
        checkout scm
        sh 'cat Jenkinsfile'
        echo 'Building dev'
    }
    stage('Test') {
        sh 'cat Jenkinsfile'
        echo 'Testing dev'
    }
    stage('Deploy') {
        echo 'Deploying dev'
    }
}
