pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'date'
            sh 'y = "1\\\\n 2\\\\n 3\\\\n 4".split("\\n")[-2].trim()'
          }
        }
        stage('Test1') {
          steps {
            sh 'out = cat /User/sityagi/Desktop/test.properties'
            sh '$out | grep faovm.smc.HOST_FA'
          }
        }
      }
    }
  }
}