pipeline {
    agent any
    environment { 
        CI = 'true'
    }
    stages {
        stage('Deliver') { 
            steps {
                input message: 'Finished using the web site? (Click "Proceed" to continue)' 
            }
        }
    }
}
