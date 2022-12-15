pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "aws cloudformation create-stack --stack-name test-stack-for-ec2-update --template-body file://ec2_instance_pract.yml --region us-east-1"
            }
        }    
    }
}    