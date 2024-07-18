
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.8-eclipse-temurin-21-alpine' } }
    environment {
        JAVA_HOME = '/usr/lib/jvm/openlogic-openjdk-17-hotspot/'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}