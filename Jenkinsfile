pipeline {
    agent {
        docker {
            image 'maven:3.3.3'
            label 'my_docker'
        }
    }
    stages {
        stage('build') {            
            steps {                
                sh 'mvn --version'            
            }        
        }    
    }
}
