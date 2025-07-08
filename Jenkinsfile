pipeline{
    agent any 
    stages{
        stage('Build'){
            steps{
                echo "perform this stage untill success"
                retry(3){
                echo "This is not correct way"
                error "continue this stage"
                }
            }
        }
    }
}
