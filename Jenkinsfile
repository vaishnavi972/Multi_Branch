node('master') 
{
    stage('ContinuousDownload') 
    {
        git 'https://github.com/vaishnavi972/maven.git'
    }
    stage('ContinuousBuild') 
    {
        sh 'mvn package'
    }
}
