pipeline {
    agent any
    tools { nodejs "node" }
     environment {
            CI = 'true'
        }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm start'
            }
        }
      
               
           

    }
}
