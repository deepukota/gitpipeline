pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Example2'){
            steps{
                copy(file:"C:\Anudeep\test.txt", tofile:"C:\Anudeep\Software\test.txt")
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
