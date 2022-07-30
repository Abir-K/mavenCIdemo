pipeline {
    agent any
    
    tools {
        maven 'maven-3.6.3'
    }
    environment {
        PATH = "/usr/bin:$PATH"
    }

    stages {
        stage("build") {
            steps {
                sh "mvn clean install"
            }
        }

        stage("test") {
            steps {
                echo "Hellow From! testing phase for maven"
            }
        }
    }
}
