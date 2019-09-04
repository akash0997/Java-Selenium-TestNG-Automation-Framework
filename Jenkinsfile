pipeline {
agent any
    tools {
        maven 'mymaven' 
    }
    stages {
       stage ('Test') {
          steps {
               sh 'mvn clean test'
               }
           }
       }
}
