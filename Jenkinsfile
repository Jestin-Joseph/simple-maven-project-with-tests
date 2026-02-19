pipeline {
  agent any
  tools { maven 'M3' }
  stages {
    stage('Checkout') { steps { checkout scm } }
    stage('Build & Test') { steps { sh 'mvn -B test package' } }
  }
}
