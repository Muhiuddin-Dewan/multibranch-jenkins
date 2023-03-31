pipeline{
    agent any
    stages{
        stage('hello'){
            steps{
                echo "hello from branch 3"
            }
        }
        stage('world'){
            steps{
                echo "hello world from other side of branch 3"
            }
        } 

        stage('from me'){
            steps{
                echo "hello from me"
            }
        }      
    }
}