// def qgFail
// def serviceTraceName
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deployment steps here
            }
        }
         stage('Sonar Analysis') {
            // Sonar Scan
                       steps {
                echo 'Deploying...'
                // Add your deployment steps here
            }
          }
          stage('Sonar Quality Gate Check'){
            // Sonar qaulity gating, fails build if sonar gate fail
                        steps {
                echo 'Deploying...'
                // Add your deployment steps here
            }
          }  
    }
}
