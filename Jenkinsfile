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
}

