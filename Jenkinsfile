pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                print 'Hello World'
            }
        }
        stage('DevBuild') {
            steps {
                print 'This is for DevBuild Satge'
                git branch: 'main', credentialsId: 'GitHubCredentials', url: 'https://github.com/priyankamavanoor/groovy-training'
            }
        }
        stage('SitBuild') {
            steps {
                print 'This is for SitBuild Satge'
            }
        }
        stage('UATBuild') {
            steps {
                print 'This is for UATBuild Satge'
            }
        }
        stage('ProdBuild') {
            steps {
                print 'This is for ProdBuild Satge'
            }
        }
        
    }
}
