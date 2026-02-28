pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: 'https://github.com/BSDeeksha2005/jenkins-pipeline-demo.git',
                    branch: 'main'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }
    }
}
