pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "aws cloudformation create-stack --stack-name test-stack-for-ec2-webhook --template-body file:/ec2-instance_pract.yml --region us-east-1"
                echo "webhook added to check automation"
            }
        }    
    }
}    