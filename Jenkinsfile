pipeline {
    agent any
    options {
        disableConcurrentBuilds() // Zapobiega równoczesnym wykonaniom tego samego pipeline
    }
    stages {
        stage('Example Stage') {
            steps {
                script {
                    // Symulacja długotrwałego procesu...
                    echo 'Wykonuje długotrwały proces...'
                    sleep(time: 20, unit: 'SECONDS')
                    echo 'Proces zakończony.'
                }
            }
        }
    }
}
