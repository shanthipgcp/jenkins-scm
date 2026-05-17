pipeline{
    agent any
    stages{
        stage('Build') {
                steps {
                    retry(3){
                              echo "Hello from Jenkins SCM pipeline"
                            error "this will give some error"
                    }
                echo "This will be executed after retry block"
                }        
            }
    }
}
