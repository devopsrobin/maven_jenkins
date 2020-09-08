node('master') 
{
    stage('ContinuousDownload:Multi1') 
    {
        git 'https://github.com/devopsrobin/git_jenkins.git'
    }
    stage('ContinuousBuild:Multi1') 
    {
        sh label: '', script: 'mvn package'
    }
}
