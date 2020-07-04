pipeline {
    agent any
    stages {
        stage ('Compile Stage') {

            steps {
                sh 'mvn clean package'
               
            }
        }
        stage ('Testing Stage') {

            steps {
               
                    sh 'mvn test'
                
            }
        }
       
        
    }
}
