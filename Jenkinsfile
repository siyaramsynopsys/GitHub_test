pipeline {
    agent any
    
    stages {
        stage("blackduck-security-scan") {
           steps {
               script {
                   security_scan  product: 'blackducksca',include_diagnostics: true
                    
                }
            }           
        }
    }
}
