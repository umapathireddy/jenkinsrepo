pipeline {
    agent any
	tools {
		maven 'Maven'
		jdk 'JDK 1.8'
	}
    stages {
        stage('clean') {
            steps {
                echo 'cleaning..'
		bat 'mvn clean'
            }
        }
        stage('Package') {
            steps {
                echo 'Testing..'
		bat 'mvn package'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}