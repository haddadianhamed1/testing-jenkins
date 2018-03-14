node {
  stage('testing') {
    checkout scm
    echo "hello"
    sh 'ls'
    sh 'echo $BUILD_ID'
    sh 'echo $JOB_NAME'
    sh 'echo $JENKINS_HOME'
    sh 'export AWS_ACCESS_KEY_ID=$accesskey'
    sh 'export AWS_SECRET_ACCESS_KEY=$secretkey'
    sh 'echo $AWS_ACCESS_KEY_ID'
  }
}
