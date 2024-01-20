pipeline{

agent { node { label 'workstation' }


stages{

  stage('build'){
    steps{
       sh 'mvn package'
       echo 'build'
    }
}
  stage('unit test'){
      steps{
       // sh 'mvn test'
        echo 'unit test'
      }
  }
  stage('code analysis'){
      steps{
        echo 'code analysis'
      }
  }

  stage('security scans'){
      steps{
        echo 'security scans'
      }
  }

  stage('artifact creation'){
      steps{
        echo 'artifact creation'
      }
  }
}



}