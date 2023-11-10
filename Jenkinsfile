pipeline {
  agent any

  stages {
      stage('Build Artifact') {
            steps {
              sh "mvn clean package -DskipTests=true"
              archive 'target/*.jar' 
            }
        }   
       stage('Unit Tests') {
            steps {
              sh "mvn test"
            }
        }   
        stage('Teste Uniti) {
            steps {
              sh "mvn test"
            }
        }   
    
    }
}