node('Dev') 
{
    stage('Continuous Download Loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build loans') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
