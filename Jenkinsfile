pipeline {
    agent any
    
    environment {
        PATH = "/usr/bin:$PATH"
    }

    stages {
        stage("build") {
            steps {
                echo "Hello! From Build Phase"
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
