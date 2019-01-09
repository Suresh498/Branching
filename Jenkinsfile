node{
	stage('SCM Checkout'){
	git 'https://github.com/Suresh498/Branching.git'
	}
	stage('Compile-package'){
	def mvnhome = tool name: 'M2_HOME', type: 'maven'
		sh "${mvnhome}/bin/mvn package"
	}
}
