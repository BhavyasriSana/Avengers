pipeline {
    libraries{
        lib 'shlib'
    }
    agent any
    stages{
     stage('SONARQUBE'){
            steps{
                script{
    
                    String result=Metrics(JSON)
                    //int pull=gitpullrequest(JSON)
                    print result
                    //Score(JSON,result,pull)
    }
               
            }
            }
            }
            }
