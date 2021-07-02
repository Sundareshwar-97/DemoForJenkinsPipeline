pipeline
{
    agent any
    environment
    {
        NAME="Sundar"
    } 

    stages
    {
        stage('Python')
        {
            steps
            {    
            sh "scriptpy.py"
            }
        }
    
        stage('Shell')
        {
            steps
            {
            sh "./script.sh"
            }
        }
    }
}
