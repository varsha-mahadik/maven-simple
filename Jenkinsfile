pipeline {
    agent any

    stages {
        stage('Build') 
		{
            steps 
			{
                echo 'Buiild success'
            }
        }
		
		 stage('Test') 
		{
            steps 
			{
                echo 'Buiild success'
            }
        }
		
		 stage('Deploy') 
		{
            steps 
			{
                echo 'Buiild success'
            }
        }
    }
	post{
	always
	{
		emailext body: 'success', subject: 'pipeline status', to: 'mahadikvarsha16@gmail.com'
	}
	}
	
    }
