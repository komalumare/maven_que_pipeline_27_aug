pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/komalumare/maven_que_pipeline_27_aug.git'

            }

        }
        stage('maven run') {
            steps {
                bat "mvn clean install"

            }

        }
    }
}
