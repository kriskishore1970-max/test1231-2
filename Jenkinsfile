pipeline {

  agent any

  stgaes {

        stage ("checkOut") {
      steps {
        echo 'checkOut application'
      }
    }
    stage ("build") {
      steps {
        echo 'building application'
      }
    }
        stage ("test") {
      steps {
        echo 'test application'
      }
    }
        stage ("deploy") {
      steps {
        echo 'deploy application'
      }
    }
            stage ("cleanUp") {
      steps {
        echo 'cleanUP application'
      }
    }
  }
}
