node {
    // checkout scm
    /*
     * In order to communicate with the MySQL server, this Pipeline explicitly
     * maps the port (`3306`) to a known port on the host machine.
     */
    // docker.image('salakhaliffjr/php-apache-plain:latest').withRun('-dit -p 7000:80') {
    //     /* Wait until mysql service is up */
    //     // sh 'while ! mysqladmin ping -h0.0.0.0 --silent; do sleep 1; done'
    //     /* Run some tests which require MySQL */
    //     // sh 'make check'
    //     echo 'Container Deployed in port 7000'
    // }
    stage('Deploying Docker Image'){
        docker.image('salakhaliffjr/php-apache-plain:latest').withRun('-dit -p 7000:80')
    }
}