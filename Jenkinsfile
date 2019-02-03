pipeline {
    agent any
    stages {
        stage ("Girl Friend") {
            steps {  git 'https://github.com/pandian3k/Maven-Demo.git' }
        }
        stage ("bestty") {
            steps {  bat label: '', script: 'mvn clean'
            bat label: '', script: 'mvn install'  }
        }
        stage ("droped") {
            steps { bat label: '', script: 'xcopy /y "C:\\Program Files (x86)\\Jenkins\\workspace\\demo-pipe-01\\multi-module\\webapp\\target\\webapp.war" "C:\\Program Files\\Apache Software Foundation\\Tomcat 8.5\\webapps"' }
        }
    }
}
