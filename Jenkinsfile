node {
  stage('testing') {
    checkout scm
    echo "hello"
    ls
    echo $BUILD_ID
    echo $JOB_NAME
    echo $JENKINS_HOME
    export AWS_ACCESS_KEY_ID=$accesskey
    export AWS_SECRET_ACCESS_KEY=$secretkey
    aws s3 sync . s3://app.cherinehaddadian.com --delete
  }
}
