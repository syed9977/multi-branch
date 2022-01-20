pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload-Loans')
        {
            steps
            {
                git 'https://github.com/intelliqittrainings/maven.git'
            }
        }
        stage('ContinuousBuild-Loans')
        {
            steps
            {
                sh 'mvn package'
            }
        }
}
