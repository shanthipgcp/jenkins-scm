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
                    //if condition
                    if(course == "K8s"){
                        println "Hey, Arjun buddy!! Thanks for enrolling to ${course} course"
                    }
                    else{
                        println "Hey, Arjun buddy!! Please do enroll to ${course} course"
                    }

                    //println "Hey, Arjun buddy!! Thanks for enrolling to ${course} course"
                }
            }
        }
    }
}
