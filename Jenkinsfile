pipeline {
    agent any
    stages {
        stage ('---clean---') {
            steps {
                bat "mvn clean"
            }
        }
        stage {
            steps ('---test---') {
                bat "mvn test"
            }
        }
        stage {
            steps ('---package---') {
                bat "mvn package"
            }
        }        
    }
}
