pipeline{
    agent{
        label "node-1"
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
