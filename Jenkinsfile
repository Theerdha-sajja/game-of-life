pipeline{
		agent any
	stages{
		       stage('clean'){
			               
					steps{
	                                         sh "mvn --version"
						 sh "java --version"
						sh "git --version"
						sh "ls"
						sh "mvn clean"
					      }
				            }
		         stage('compile'){
			               
					steps{
						sh "mvn compile"
					      }
				            }
		         stage('package'){
			               
					steps{
						sh "mvn package"
					      }
				            }

			   }
	    }
