node {
  checkout scm
  echo "current branch: $BRANCH_NAME"
  if (BRANCH_NAME.startsWith("dev")) {
    sh "echo dev1"
  } else {
    sh "echo prod1"
  }
}
