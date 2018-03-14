node {
  stage('testing') {
    checkout scm
    echo "hello"
    sh 'ls'
    sh 'echo $BUILD_ID'
    sh 'echo $JOB_NAME'
    sh 'echo $JENKINS_HOME'
    sh 'AWS_ACCESS_KEY_ID=$accesskey AWS_SECRET_ACCESS_KEY=$secretkey aws s3 sync . s3://app.cherinehaddadian.com --delete'
  }
}
