pipeline{
    agent any
    stages{
        stage(gitcheckout){
            steps{
                script{
                  checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'Gitcredentials', url: 'https://github.com/v4venu/sample1.git']]])
                }
            }
        }
    }
}

