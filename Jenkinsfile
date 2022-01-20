pipeline
{
    agent master
    stages
    {
        stage('ContinuousDownload-Master')
        {
            steps
            {
                git 'https://github.com/syed9977/multi-branch.git'
            }
        }
        stage('ContinuousBuild-Master')
        {
            steps
            {
                sh 'mvn package'
            }
        }
}
