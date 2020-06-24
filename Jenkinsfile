pipeline {
   agent any

   stages {
      stage('Hello') {
         when{
            changeRequest()
         }
         steps {
            echo 'Hello World changelog done'
         }
      }
   }
}
