pipeline
{
    agent any

    stages
    {
        stage ('continous download')
        {
            steps
            {
                git branch: 'maven_project', url: 'https://github.com/keshavr21/maven_test.git'
            }
        }
        stage ('continous build')
        {
            steps
            {
                sh 'mvn package'
            }
        }


    }

}
