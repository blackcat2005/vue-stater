pipeline {
    agent {
      label: 'vps-1'
    }

    stages {
        stage('Info') {
            steps {
                sh(script: """ whoami;pwd;ls -la; """, label: "first step")
            }
        }
    }
}
