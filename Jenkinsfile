pipeline
{
    agent any
    stages
    {
        stage('Build')
        {
            when
            {
                changeset GLOB: '*.js'
            }
            steps
            {
                echo "Hello world change set"
            }
        }
    }
}