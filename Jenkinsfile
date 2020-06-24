pipeline {
   agent any

   stages {
      stage('Hello') {
         when{
            changelog(".*some*.")
         }
         steps {
            echo 'Hello World changelog done'
         }
      }
   }
}
