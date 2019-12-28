pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'building war file'
            }
            steps{
                echo 'copying war file'
            }
        }
       
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
