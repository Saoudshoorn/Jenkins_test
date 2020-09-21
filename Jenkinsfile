node {
	stage('Checkout GITHUB') {
	checkout scm
		
	}
	stage('Build'){
		sh "docker build -t flask-alpine:1 ."
	}
	
	stage('Test'){
	}
	
	stage('Deploy'){
	}
}
