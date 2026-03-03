pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: 'https://github.com/Jnyanesh/jenkins-simple-demo.git',
                    branch: 'main'
            }
        }

        stage('Run Script') {
            steps {
                bat 'script.bat'
            }
        }

    }
}
