pipeline {
    agent any
    environment {
        JAVA_HOME = '/usr/lib/jvm/openlogic-openjdk-17-hotspot/'
    }
    stages {
        stage('Build') {
            steps {
                sh '/opt/apache-maven-3.9.8/bin/mvn -B -DskipTests clean package'
            }
        }
    }
}