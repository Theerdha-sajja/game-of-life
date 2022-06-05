pipeline{
		agent any
	stages{
		       stage('three'){
			               cd game-of-life
					steps{
						//bat "git clone   https://github.com/Theerdha-sajja/Pipeline.git"
					        sh "mvn validate"
					      }
				     }
		       stage('four'){
					 steps{
					        sh "mvn compile"
					      }
				    }							
		       stage('five'){
					 steps{
					        sh "mvn package"
					      }
                			}
			   }
	    }
