pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo"this is build stage"
                bat 'msbuild C:\\Users\\Shrikant Alone\\Desktop\\shrikant\\dotnetproject\\DemoDotNetProject /t:Rebuild /p:Configuration=Release'
                
                }
            }
        }
    }
