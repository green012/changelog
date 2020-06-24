pipeline {
   agent any

   stages {
      stage('Hello') {
         when{
            changeset glob: "*.js"
         }
         steps {
            echo 'Hello World changeset is done'
         }
      }
   }
}
