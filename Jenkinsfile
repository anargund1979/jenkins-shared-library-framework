@Library('dcube-library@master') _
 
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "master",
                url: "https://github.com/anargund1979/jenkins-shared-library-framework.git"
            )
            }
    }
    }
}
