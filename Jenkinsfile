pipeline {
	environment {
		//registry = "varma03/node-frontend"
		//registryCredential = 'dockerhub'
		//dockerImage = ''
		dockerRegistry = 'sankalpreddy/eshoponweb'
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
	      script {
		      sh "echo ${dockerRegistry}"
	      }
      }
    }
  } //stages
} //pipeline
