pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'date'
        sh '''y = "1\\n 2\\n 3\\n 4".split("\\n")[-2].trim()
println y'''
      }
    }
  }
}