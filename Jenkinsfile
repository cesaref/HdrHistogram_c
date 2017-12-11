node {
    stage('Checkout') {
        checkout scm
    }

    stage('Build') {
        sh 'mkdir build'
        sh 'cd build'
        sh 'cmake ..'
        sh 'make'
        sh 'make test'
    }
}
