pipeline {
	environment {
		//registry = "varma03/node-frontend"
		//registryCredential = 'dockerhub'
		//dockerImage = ''
		dockerRegistry = 
	}
	
	//Docker hub repo name
	//def registry = "sankalpreddy/eshoponweb"
	
	agent any

	options {
		skipDefaultCheckout false
		//buildDiscarder(logRotator(numToKeepStr: '5'))
	}
  
  stages {
    stage('Testing') {
      steps {
		    checkout scm
      }
    }
  } //stages
} //pipeline
