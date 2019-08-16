pipeline {
	agent any
	stages{
		stage('Build'){
			steps{
				sh 'mvn clean package'	
				sh "sudo -S <<< "sachin123" docker build . -t tomcatwebapp:${env.BUILD_ID}"
			}		
		}
	}
}
