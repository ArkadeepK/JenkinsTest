pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo 'building'   
            }
        }
        stage("ship"){
            steps{
                echo 'shipping'  
                cred = credentials("MySecret")
                echo "Secret = ${cred}"
            }
        }
    }
}
