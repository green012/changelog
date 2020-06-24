pipeline {
   agent any

   stages {
      stage('Hello') {
         when{
            changeset "*.js"
         }
         steps {
            echo 'Hello World changeset is done'
         }
      }
   }
}
