pipeline{
    agent any
    stages{
        stages("build"){

            steps{
                echo 'building the application'
                
            }
        }
        stages("test"){
            steps{
                echo 'testing the application'
            }
        }
        stages("deploy"){
            steps{
                echo 'deplying the application'
            }
        }
    }
    post{
        always{
            //
        }
        failure{
            
        }
    }
}