pipeline{
          stage('Checkout'){
            //Checkout the code from a GitHub repository
            git credentialsId: 'suresh498', url: https://github.com/Suresh498/Branching.git
          }
          stage('build'){
            sh 'mvn -V clean compile'
          }
          stage('test'){
            sh 'mvn -V clean test'
          }
}															                  }
																							                   }
																									   	stage('Install stage') 
																												{
																												            steps {
																													    				sh 'mvn install'
																																			  }
																																			  		 }
																																					 	}
																																						}
