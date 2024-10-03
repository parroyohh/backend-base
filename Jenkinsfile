pipeline {
    agent any
    stages{
        stage('etapa de construccion de aplicacion'){
            agent {
                docker {
                    image 'node:alpile3.20'
                }
            }
            stages{
                stages("install"){
                    steps{
                        sh 'npm install'
                    }
                }
            }
        }
    }
}
