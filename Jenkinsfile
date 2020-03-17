pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
        stage('powershell'){
            steps{
                powershell 'Write-Output "Hello, World! powershell"'
                
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again bbb!'
        }
    }
}
