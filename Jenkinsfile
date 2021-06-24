pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                echo '1st step in build step'
                sleep 3
            }
        }
        stage('Test'){
            steps{
                echo 'Test'
                sleep 5
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploy'
                sleep 2
            }
        }
        
    }
}
