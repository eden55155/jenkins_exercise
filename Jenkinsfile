pipeline {
agent any
stages {
    stage('Terraform init and apply'){
        steps {
            sh 'terraform init'
            sh 'terraform apply --auto-approve'
        }
    }
}
}