pipeline {
    agent {
        node {
            label 'maven'
        }
    }
environment {
    PATH = "/usr/share/apache-maven-3.6.3/bin:$PATH"
}
    stages {
        stage("build"){
            steps {
               sh 'mvn clean deploy'
            }
        }
    }
}
