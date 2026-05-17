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
                def course = "K8s"
                println "Thanks for enrolling to ${course} course"
            }
        }
    }
}
