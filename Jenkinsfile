node {
    stage('Checkout') {
        checkout scm
    }

    stage('Build') {
        sh '''rm -rf build
              mkdir build
              cd build
              cmake ..
              make
              make test'''
    }
}
