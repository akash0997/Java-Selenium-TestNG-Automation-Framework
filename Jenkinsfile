pipeline {
agent any
    tools {
        maven 'mymaven' 
    }
    stages {
       stage ('Test') {
          steps {
               bat 'mvn clean test -Pdev'
               }
           }
       }
}
