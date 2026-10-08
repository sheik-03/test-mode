pipeline{
    agent any
    stages{
        stage("github"){
            steps{
                git credentialsId: 'python-code', url: 'https://github.com/sheik-03/test-mode.git'
            }
        }
        stage("build"){
            steps{
                sh 'python3 --version'
            }
        }
        stage("test"){
            steps{
                echo "welcome to testing team"

            }
        }
        stage("deploy"){
            steps{
                sh 'python3 app.py'''
            }
        }
    }
}
