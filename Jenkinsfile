pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "${env.BRANCH_NAME} - ${env.GIT_COMMIT}"
         }
      }
   }
}
