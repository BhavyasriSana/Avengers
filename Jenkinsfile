pipeline {
    libraries{
        lib 'shlib'
    }
    agent any
    stages{
     stage('SONARQUBE'){
            steps{
                Metrics(JSON)
                SCORE(JSON)
            }
            }
            }
            }
