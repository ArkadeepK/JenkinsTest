pipeline{
    agent any
    environment{
        CRED = credentials("MySecret")
    }
    stages{
        stage("build"){
            steps{
                echo 'building'   
            }
        }
        stage("ship"){
            steps{
                echo 'shipping'  
                echo CRED
            }
        }
    }
}
