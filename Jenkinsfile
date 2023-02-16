pipeline{
   
    agent any

    stages {
        
        stage("build"){
            steps{
                echo 'Building your project...'
            }
            
        }
        stage("test"){
            when{
                expression{
                    BRANCH_NAME == 'master'
                }

            }
            steps{
                echo 'Testing in progress.......'
            }
        }
         stage("deploy"){
            steps{
                echo 'Deployment in progress.......'
            }
        }


    }


}