pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                echo 'compiling..'
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn compile'
                }
            }
        }
        
    }
}
