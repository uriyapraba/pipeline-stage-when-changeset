pipeline
{
    agent any
    stages
    {
        stage('Build')
        {
            when
            {
                changeset pattern: "*.js"
            }
            steps
            {
                echo "Hello world change set"
            }
        }
    }
}