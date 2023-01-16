pipeline {
    agent any

    stages 
    {
        stage('Build') 
        {
            steps
            {
                echo 'Building a app'
            }
        }
        stage('Test') 
        {
            steps
            {
                echo 'testing a app'
            }
        }
        stage('deploy') 
        {
            steps
            {
                echo 'deploy a app'
            }
        }
        
    }
    post
    {
        always
        {
            emailext body: 'dsfsadf', subject: 'hiii', to: 'lavanyamn216@gmail.com'
        }
    }
}
