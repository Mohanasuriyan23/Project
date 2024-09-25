pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
            }
        }

        stage('update my this part') 
        {
            steps 
            {
                echo 'Test App'
            }
        }

        stage('Hello  kolavari webhook for Jenkins project ') 
        {
            steps 
            {
                echo 'Deploy App'
            }
        }
    }

    post
    {

    	always
    	{
    		emailext body: 'Summary', subject: 'Pipeline Status', to: 'mohanasuriyan@gmail.com'
    	}

    }
}
