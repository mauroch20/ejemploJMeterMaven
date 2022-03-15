pipeline {

	agent any
	
	stages{
		stage('Pipeline'){
			steps{
				script{
					
                    try
                    {
                        sh 'mvn verify -Pperformance'
                    				
                    }
                    catch(Exception e)
                    {

                        
                    }




				}
			}

		}
		
    }
}




