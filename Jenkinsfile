pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'date'
        sh '''d = "1\\n 2\\n 3\\n 4"
y = d.split("\\n")[-2].trim()
println y'''
      }
    }
  }
}