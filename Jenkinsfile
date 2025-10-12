pipeline {
    agent any
    stages {
        stage('Clean Workspace') {
            steps {
                deleteDir()
            }
        }
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Ravali1411/blood-bank-app.git'
            }
        }
	stage("Code" {
	    steps {
		git "https://github.com/devops0014/ltibbhackathon.git"
    }
}

