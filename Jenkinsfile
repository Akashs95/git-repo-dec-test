pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "aws cloudformation create-stack --stack-name test-stack-for-ec2-creation-using-jenkins-pipeline --template-body file://ec2-instance_pract.yml --region us-east-1"
            }
        }    
    }
}    