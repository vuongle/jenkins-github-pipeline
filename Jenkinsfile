pipeline{
    agent any
    triggers {
        githubPush()
    }
    stages{
        stage("Clone"){
            steps{
                git 'https://github.com/vuongle/jenkins-github-pipeline.git'
            }
        }
    }
}