pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Biuilding a project'
            }
        }
        stage('test') {
            steps {
                echo 'testing a project'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying project'
            }
        }
        stage('Done') {
            steps {
                echo 'completed'
            }
        }
    }
}
