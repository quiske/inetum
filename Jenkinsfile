// Pipeline declarativo
pipeline {
    
    // Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    //Fases
    stages {
        
        stage('Build') {
            //Pasos de la fase
            steps {
                echo "Build artifact"
            }
        }
        stage('Testing') {
            //Pasos de la fase
            steps {
                echo "Test Unitarios..."
                echo "Test Integracion..."
                echo "Test Aceptacion..."
            }
        }
        
        stage('Deploy') {
            //Pasos de la fase
            steps {
                echo "Deploy artifact"
            }
        }
    }
    
    
}
