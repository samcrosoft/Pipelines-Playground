pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      agent any
      steps {
        sh '''echo "today is %{date}"
echo "start up now"'''
      }
    }

  }
  environment {
    NUMBERONE = '10'
    NUMBERTWO = '20'
  }
}