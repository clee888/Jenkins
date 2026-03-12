pipeline {
  agent any
  
  stages {
    stage('check service') {
      steps {
        powershell """
        get-service -name bits*
        Get-WmiObject win32_operatingsystem | select @{LABEL=’LastBootUpTime’;EXPRESSION={$_.ConverttoDateTime($_.lastbootuptime)

        """
      }
    }
  }
}
        
