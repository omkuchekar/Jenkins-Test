pipeline {
    agent any

    stages {
        stage("checkout"){
            steps {
                echo "checkout git repo"
                sh 'git checkout https://gitlab.com/omkuchekar/aws-terraform.git'
                
            }
        }
    }
}