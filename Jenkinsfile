pipeline {
    agent any 
    
    stages {
        stage('Dev Git') {
	when {
                branch 'Dev'
            }
		
            steps { 
		    echo "*************in Dev"
		    git 'https://github.com/RAMSHANKARMCA08/MultiBranchPipeline.git' }
        }
	    
	 stage('QA Git') {
	   when {
                 branch 'QA'
                }		
             steps { 
		     echo "**************In QA"
		     git 'https://github.com/RAMSHANKARMCA08/MultiBranchPipeline.git'
		   }
        }
	
    }
}
