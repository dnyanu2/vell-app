pipeline{
    agent{
        label "buit-in"
    }
    stages{
        stage('deploy'){
            steps{
                sh "cp -r index.html /var/www/html"
                sh "chmod -R 777 index.html"
            }
        }
    }
}
