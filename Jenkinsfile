pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
                echo 'Cleaning..'
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn clean'
                }
            }
        }
        
    }
}
