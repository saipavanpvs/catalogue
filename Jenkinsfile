pipeline {
    agent any
    stages {
        stage ('Lint checks for node Js'){
            steps{
            sh "echo Installing JS Lint"
            sh "npm -i jslint"
            sh "/home/centos/node_modules/jslint/bin/jslint.js server.js "
            }
        }
    }
}

