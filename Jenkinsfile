node {
  checkout scm
  echo "current branch: $BRANCH_NAME"
  if (BRANCH_NAME=="dev") {
    sh "echo dev"

  } elseif (BRANCH_NAME=="prod"){
    sh "echo prod1"
  } else {
    sh "echo master"
  }
}
