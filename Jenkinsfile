pipeline {
    agent any
    tools {
        maven 'Maven 3.8'
        jdk 'jdk 11'
    }
    stages {
        stage('Initialize') {
            steps {
                bat '''
                    echo "PATH = ${PATH}"
                    echo "JAVA_HOME" = ${JAVA_HOMEs}
                    echo "MAVEN_HOME = ${MAVEN_HOME}"
                '''
            }
        }
        stage('Build') {
            steps {
                echo 'Build'
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Package') {
            steps {
                echo 'Package'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
    }
}
