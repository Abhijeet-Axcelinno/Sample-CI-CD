pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building...'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
        }
   }
   stage('Test') {
     steps {
        echo 'Testing...'
     }
   }
   stage('Acceptance Test') {
     steps {
        echo 'Testing...'
     }
   }
   stage('Staging') {
     steps {
        echo 'Deploying...'
     }
   }
   stage('Production') {
     steps {
       echo 'Deploying...'
     }
   }
   stage('Smoke Test') {
     steps {
       echo 'Testing...'
     }
   }
  }
}