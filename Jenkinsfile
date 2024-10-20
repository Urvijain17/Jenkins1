pipeline {
  agent any

  stages {
    stage( "hello" ) {
      steps {
        bat "javac HelloWorld.java"
      }
    }

    stages {
      stage {
        bat "java HelloWorld"
      }
    }
    
  }
}
