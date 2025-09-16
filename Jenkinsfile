pipeline {
    agent any

    stages {
        stage('Git Pull') {
            steps {
                git branch: 'main', url: 'https://github.com/Mraakhil/vpc.git'
            }
        }

        stage('Terraform Init') {
            steps {
                sh 'terraform init'
            }
        }
    }

      stage('Terraform plan') {
            steps {
                sh 'terraform plan'
            }
        }
    }

   stage('Terraform apply') {
            steps {
                sh 'terraform apply'
            }
        }
    
}

