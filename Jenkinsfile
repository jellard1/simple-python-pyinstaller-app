pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker {
#                    image 'python:2-alpine' 
                    image 'jenkins-slave' 
                }
            }
            steps {
#                sh 'python -m py_compile sources/add2vals.py sources/calc.py' 
                 sh "echo 'hello'"
            }
        }
    }
}
