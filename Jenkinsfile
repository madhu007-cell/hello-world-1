pipeline{
    agent any
    environment{
    PATH = "C:\\DevTools\\apache-maven-3.6.3\\bin"
    }
    stages{
        stage("SCM checkout"){
            steps{
                git 'https://github.com/vasu7github/hello-world.git'
            }
        }
        stage("maven Build"){
            steps{
                bat "mvn clean package"
            }
        }
    }
}
