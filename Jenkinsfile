node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/lakshmipathi18/maven.git'
	}
    stage('Continuous Builds') 
	{
    sh label: '', script: 'mvn package'
	}
}
