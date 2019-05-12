@Library('global-shared-library') _
pipeline {
  agent any

  stages {
    stage('Build') {
        steps {
//            echo "${createVersion(BUILD_NUMBER)}"
            sayHello("world")
            script {
                def util = new codes.showme.Utils()
                def v = util.getVersion("${BUILD_NUMBER}", "${GIT_COMMIT}")
                echo "${v}"
            }
        }
    }
  }

}

// def createVersion(String BUILD_NUMBER) {
//     return new Date().format('yyMM') + "-${BUILD_NUMBER}"
// }
