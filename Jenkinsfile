pipeline {
  agent any
  stages {
    stage ("build") {
      steps {
        echo "building my app..."
        sh npm install
      }
    }
    stage ("test") {
       steps {
        echo "testing my app..."
       }
    }
    stage ("deploy") {
    steps {
        echo "deploying my app..."
       }
    }
  }

}