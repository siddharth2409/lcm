pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'date'
        sh '''d = [
    1,
    2
];
y = d.split("\\n")[-2].trim()
println y'''
        }
      }
    }
  }