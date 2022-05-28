pipeline{
    agent any
    stages{
        stage{
            steps('build'){
                sh 'echo Hello World'
            }
        }
        stage{
            steps(test){
                sh 'testing the environment'
            }
        }
    }
}