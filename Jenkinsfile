pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$env.GIT_COMMIT - $BRANCH_NAME"
            echo "${env.BRANCH_NAME} - ${env.GIT_COMMIT}"
         }
      }
   }
}
