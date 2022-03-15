pipeline {

	agent any
	
	environment{
        STAGE=''
    }

	parameters {
  		choice choices: ['gradle', 'maven'], description: 'Indicar herramienta de contrucción', name: 'buildTool'
	}	

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




