pipeline {
   agent any
   stages{
    stage('CodeScan'){
        steps{
            sh 'trivy fs . -o result.hmtml'
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