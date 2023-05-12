pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "executing the path specified by the environment variable, getting the original source code within the directory."

                echo "executing the code and producing any required outputs."
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "putting into practise unit tests."
                echo "integrating testing through execution."
            }
        }

        stage('Code Analysis') {
            steps {
                echo "assessing the standard of the code using a code evaluation tool."
            }
        }

        stage('Security Scan') {
            steps {
                echo "finding flaws by using a security scanning programme."
            }
        }
finding flaws by using a security scanning programme.
        stage('Integration Tests on Staging') {
            steps {
                echo "The staging environment is being put through integrity tests."
                
            }
        }

        stage('Deploy to Production') {
            
            steps {
                echo "bringing the code into the operational environment."
            }
        }
    }

    post {
        always {
            mail to: "ishitajoshi144@gmail.com",
            subject: "Status",
            body: "Build log"
        }
    }
}
