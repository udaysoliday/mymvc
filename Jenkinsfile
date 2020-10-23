pipeline {
    agent any 
    stages {        
        stage('---clean---') { 
            steps {                               
                "mvn clean"
            }
        }
        stage('---Test--') { 
            steps {
                "mvn test"
            }
        }
        stage('---Deploy---') { 
            steps {
                "mvn package" 
            }
        }
    }
}
