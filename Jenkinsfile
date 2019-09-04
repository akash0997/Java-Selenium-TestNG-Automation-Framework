pipeline {
agent any
    tools {
        maven 'mymaven' 
    }
    stages {
       stage ('Test') {
          steps {
               sh 'PORT=9515 mvn clean test'
               }
           }
       }
}
