node {
    stage('Deploying Docker Image'){
        docker.image('salakhaliffjr/php-apache-plain:latest').withRun('-dit -p 7000:80'){
            sh 'sleep 180' 
            // Keeps the container running for 3 minutes
        }
    }
}