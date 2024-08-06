pipeline {
    agent none {
        stages {

            stage('Checkout') {
                steps {
                    git 'https://github.com/Santosh-Nijaguli/Jenkins.git'
                }
            }
            stage('Build') {
                steps {
                    echo 'Building code'
                }
            }
            stage('Test') {
                steps {
                    echo 'Testing'
                }
            }
            stage('Deploy') {

                steps {
                    echo 'Deploying'
                }
            }
        }
    }
}
