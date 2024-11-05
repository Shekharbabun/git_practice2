pipeline{
  agent any
  stages{ 

    stage ('Install Dependencies'){
      steps{
         sh 'npm install'
       }
     }
    stage ('test')
      steps {
         sh 'echo "Testing applications"'
       }
     }
    stage ('depoly')
      steps {
         sh 'echo "depolying applications"'
       }
     }
   }
 }
