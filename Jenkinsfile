node('dev') {
    stage('Checkout') {
        checkout([$class: 'GitSCM', branches: [[name: 'develop']],
                userRemoteConfigs: [[url: 'https://github.com/edmundtetteh/movies-store.git']],
                credentialsId: 'ubuntu-jenkins'])
    }

    // Add more stages
}