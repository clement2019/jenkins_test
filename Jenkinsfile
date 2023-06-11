pipeline{
    agent any
    stages{
        stage("Build docker"){
            steps{
                sh 'printenv'
                sh 'git version'
                sh '""$BUILD_ID""'
                sh 'docker build -t good777lord/imag:""$BUILD_ID"" .'
            }
        }
         
        }
    }

    
}
