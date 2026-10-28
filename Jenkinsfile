pipeline{
    agent any
    stages{
        stage("Source code"){
            steps{
                echo "this is my jenkins run"
                bat 'dir'
            }
        }
        stage("Version Control"){
            steps{
                echo "these are the versions"
                bat "git log --oneline"
            }
        }
    }
}
