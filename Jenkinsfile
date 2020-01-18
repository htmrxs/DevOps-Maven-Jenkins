Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            def = mvnHome = tool name: 'maven 3.6.3', type: 'maven'
            sh "${mvnHome}/bin/mvn package"
            steps {
                echo 'Hello world!' 
            }
        }
    }
}