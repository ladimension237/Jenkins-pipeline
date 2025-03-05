pipeline {
   agent any
   stages{
    stage('clone'){
        steps{
            sh 'echo "clone"'
            sh 'unam -r'
        }
    }
    stage('test'){
        steps{
            sh 'echo "test"'
        }
}
    stage('ceatefile'){
        steps{
            sh 'touch text-$BUILD_ID'
        }
    }
   } 

}