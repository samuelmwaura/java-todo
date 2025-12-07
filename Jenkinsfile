pipeline
{
    agent any
    tools
    {
        jdk 'jdk21'
    }
    stages
    {
        stage('Cloning the Application Repo from Github')
        {
            steps
            {
                git branch: "master", url:"https://github.com/samuelmwaura/java-todo.git"
            }
        }
    }
    
}