pipeline{
          stage('Checkout'){
            //Checkout the code from a GitHub repository
            
		  git 'https://github.com/Suresh498/Branching.git'
          }
          stage('build'){
            def mvnhome=tool name: 'M2_HOME', type: 'maven'
		  sh "${mvhome}/bin/mvn package"
          }
          stage('test'){
		  def mvnhome=tool name: 'M2_HOME', type: 'maven'
		  sh "${mvhome}/bin/mvn test"
            
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
