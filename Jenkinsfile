pipeline{
		agent any
	stages{
		       stage('three'){
			               
					steps{
						
						//sh "git fetch https://github.com/Theerdha-sajja/game-of-life.git"
						//cd "game-of-life/"
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
