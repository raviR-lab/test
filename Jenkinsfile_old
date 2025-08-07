pipeline {
  agent any
  triggers {
    pollSCM('* * * * *') 
  }
  stages {
    stage('Build') {
      steps {
        echo "Building branch ${env.BRANCH_NAME}"
        // Add your build commands
      }
    }
  }
}
