node {
  stage('testing') {
    checkout scm
    echo "hello"
    sh 'ls'
    echo $BUILD_ID
    echo $JOB_NAME
    echo $JENKINS_HOME
    export AWS_ACCESS_KEY_ID=$accesskey
    export AWS_SECRET_ACCESS_KEY=$secretkey
  }
}
