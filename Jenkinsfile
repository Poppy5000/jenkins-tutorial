pipeline{
        agent any
        stages{
          stage('Make Script exe'){
             steps{
               sh 'chmod +x ./run.sh'
             }
          }    
          stage('Run Script'){
            steps{
              sh './run.sh'
            }
          }
        }    
}
