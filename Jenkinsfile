pipeline{
    agent any
    
    stages{
        stage("Env Build Number"){
            steps{
                echo "The build number is ${env.BUILD_NUMBER}"
                echo "You can also use \${BUILD_NUMBER} -> ${BUILD_NUMBER}"                                                
            }
        }
    }
}
