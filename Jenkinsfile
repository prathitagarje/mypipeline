pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Dev from Dev Branch'
				sh 'git --version'
            }
        }
	stage('Testing') {
            steps {
                echo 'I am in Testing from Dev Branch'
				sh 'python3 --version'
            }
        }
	stage('Production') {
            steps {
                echo 'I am in Production from Dev Branch'
				sh 'docker --version'
            }
        }
    }
}
