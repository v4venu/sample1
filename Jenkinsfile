pipeline{
    agent
    stages{
        stage(gitcheckout){
            checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'Gitcredentials', url: 'https://github.com/v4venu/sample1.git']]])
        }
    }
}

