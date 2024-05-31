pipeline {
  agent any
  stages {
    stage('git checkout') {
      steps {
        git(url: 'https://github.com/abiswas-realtydynamics/CKAD-exercises', branch: 'main')
      }
    }

  }
}