node{
	stage('SCM Checkout'){
	git poll: true url: 'https://github.com/Suresh498/Branching.git'
		properties([pipelineTriggers([pollSCM('* * * * *')])])
	}
	stage('Compile-package'){
	def mvnhome = tool name: 'M2_HOME', type: 'maven'
		sh "${mvnhome}/bin/mvn package"
	}
}
