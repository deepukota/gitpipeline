pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'building war file'
            }
        }
        stage('dev'){
            echo 'stopping services in dev environment'
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
