@Library('global-shared-library') _
pipeline {
  agent any

  stages {
    stage('Build') {
        steps {
//            echo "${createVersion(BUILD_NUMBER)}"
            sayHello("world")
        }
    }
  }

}

// def createVersion(String BUILD_NUMBER) {
//     return new Date().format('yyMM') + "-${BUILD_NUMBER}"
// }
