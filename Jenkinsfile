pipeline {
  agent any 
    stages {
      stage ('My first pipeline job to print')  {
        steps {sh 'echo Hello Jenkins'}}
        
      stage ('Build the first job') {
        steps { sh 'echo code_is_building'}}

      stage ('deploy artifacts'){
        steps {sh 'echo code_is_deploying'}}
    }
}
