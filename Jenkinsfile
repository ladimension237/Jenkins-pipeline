pipeline {
   agent any
   stages{
    stage('CodeScan'){
        steps{
            sh 'trivy --version'
        }
    }
    stage('dockerImagebuild'){
        steps{
            sh 'docker -v'
        }
}
    stage('pushImage'){
        steps{
            sh 'docker ps '
        }
    }
   } 

}