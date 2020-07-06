pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_COMMIT - $BRANCH_NAME"
         }
      }
   }
}
