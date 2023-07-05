pipeline
{
    agent any
    stages
    {
        stage('Build')
        {
            when
            {
                changeset()
            }
            steps
            {
                echo "Hello world change set"
            }
        }
    }
}