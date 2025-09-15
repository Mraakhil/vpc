pipeline {
    agent any

    stages {
        stage('git pull') {
            steps {
                git branch: 'main', url: 'https://github.com/Mraakhil/vpc.git
            }
        }
    }
}
