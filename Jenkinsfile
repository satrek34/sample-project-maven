pipeline {
    agent any
    stages {
        stage("Deploy") {
            input {
                message "Ready to deploy?"
                ok "Yes"
                parameters {
                    string(name: "DEPLOY_ENV", defaultValue: "production")
                }
            }
            steps {
                echo "Deploy to the ${DEPLOY_ENV} environment."
            }
        }
    }
}
pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                // 
            }
        }
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}
