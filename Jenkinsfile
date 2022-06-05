pipeline{
		agent any
	stages{
		       stage('three'){
			               
					steps{
						sh "git remote add orgin https://github.com/Theerdha-sajja/game-of-life.git"
						sh "git pull origin master"
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
