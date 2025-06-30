pipeline {
    agent any
    stages{
        stage("hello"){
            steps{
                echo "hello coffee"
            }
        }
    }
    post{
        always{
            echo "an always execute at any stage"
        }
        success{
            echo "pipeline is success"
        }
        failure{
            echo "pipeline is failure"
        }
    }
}   
          
      
