pipeline {
  agent any
  
  stages {
    stage('check service') {
      steps {
        powershell """
        get-services -name bits*
        """
      }
    }
  }
}
        
