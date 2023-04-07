pipeline {  
    agent any
    stages  {  
        stage('INFO') {
            steps {  
                echo "Pipeline As Code"
            }  
        }
	}
	post {  
        always {
            echo "Execute Always"
        }
       success {
            echo "Success"
        }
        failure {
            echo "Failure"
        }
    }
}
