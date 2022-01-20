pipeline
{
    agent master
    stages
    {
        stage('ContinuousDownload-Loans')
        {
            steps
            {
                git 'https://github.com/syed9977/multi-branch.git'
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
