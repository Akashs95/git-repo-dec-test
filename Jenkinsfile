pipeline {
    agent any
    stages {
        stage('submit stack') {
            steps {
                sh "aws cloudformation create-stack --stack-name test-stack-for-ec2 --template-body file://ec2_instance_pract.yml --region us-east-1"
            }
        }    
    }
}    