node('Dev') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    stage('Continuous Testing') 
   
	 {

	sh label: '', script: 'echo "Testing Passed"'
	}
	stage('Continuous Deployment') 
   
	 {
		sh label: '', script: '/home/ubuntu/workspace/workspace/Multibranch_master/webapp/target/webapp.war  ubuntu@10.0.0.103:/var/lib/tomcat8/webapps/qaenv.war' 
    	}	
}
