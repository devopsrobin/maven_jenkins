node('master') 
{
    stage('ContinuousDownload:Master') 
    {
        git 'https://github.com/devopsrobin/maven_jenkins.git'
    }
    stage('ContinuousBuild:Master') 
    {
        sh label: '', script: 'mvn package'
    }
}
