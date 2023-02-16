pipeline{
   
    agent any

    environment{

        MY_NAME = 'ASHRAF'
    }

    stages {
        
        stage("build"){
            steps{
                echo 'Building your project...'
                echo "My name is ${MY_NAME}"
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