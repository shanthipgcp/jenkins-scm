pipeline{

    agent any
    stages{
        stage('Buid'){
            steps{
                echo "Hello from Jenkins SCM pipeline"
            }
        }
        stage('GrooveStage'){
            steps{
                script{
                    def course = "K8s"
                    println "Hey, Arjun buddy!! Thanks for enrolling to ${course} course"
                }
            }
        }
    }
}
