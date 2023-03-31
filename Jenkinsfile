node('master') 
{
    stage('CD-S1-payment') 
    {
    git 'https://github.com/BABJI-AWS-DEVOPS/batch42warfile.git'
    }
    stage('CD-S2-payment') 
    {
    sh 'mvn package'
    }
}
