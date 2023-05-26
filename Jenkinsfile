pipeline {
    agent any
   
    stages {
        stage('Build') {
            steps {
              sh '''
                echo 'Build de Jenkins'
                '''
            }
        }
             stage('Test') {
            steps {
              sh '''
                echo 'Test de Jenkins'
                '''
            }
        }
      
             stage('Push') {
            steps {
              sh '''
                echo 'Push de Jenkins'
                '''
            }
        }
      
             stage('Deploy to K8s') {
            steps {
              sh '''
                echo 'Deploy to k8s'
                '''
            }
        }
    }
}
