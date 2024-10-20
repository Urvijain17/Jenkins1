pipeline {
  agent any

  stages {
    stage( "hello" ) {
      steps {
        bat "javac HelloWorld.java"
      }
    }
      stage {
        bat "java HelloWorld"
      }
    
  }
}
