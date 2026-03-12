pipeline {
  agent any
  
  stages {
    stage('check service') {
      steps {
        powershell """
        get-service -name bits*
        Get-Uptime -Since
        """
      }
    }
  }
}
        
