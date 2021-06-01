node('master') 
{
    stage('Continuous Download_Loans') 
	{
    git 'https://github.com/lakshmipathi18/maven.git'
	}
    stage('Continuous Build_Loanss') 
	{
    sh label: '', script: 'mvn package'
	}
}
