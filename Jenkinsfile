node('built-in') 
{
    stage('Continuous Download_slave') 
	{
    git 'https://github.com/vbabureddy/maven.git'
	}
    stage('Continuous Build_Slave') 
	{
    sh label: '', script: 'mvn package'
	}
     
}

	
    


	

