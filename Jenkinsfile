pipeline{
    agent any
    stages{
        stage('hello'){
            steps{
                echo "hello world from sub branch"
            }
        }
        stage('world'){
            steps{
                echo "hello from other side of the main branch"
            }
        }    
    }
}