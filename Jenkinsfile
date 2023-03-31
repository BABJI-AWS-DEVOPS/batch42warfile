node('master') 
{
    stage('CD-S1') 
    {
    git 'https://github.com/BABJI-AWS-DEVOPS/batch42warfile.git'
    }
    stage('CD-S2') 
    {
    sh 'mvn package'
    }
}
