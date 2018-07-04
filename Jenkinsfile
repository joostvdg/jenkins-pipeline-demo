pipeline {
  agent any
  libraries {
    lib('jenkins-pipeline-lib')
  }
  stages {
    stage('test') {
      steps {
        echo 'hello!'
      }
    }
    stage('say hello') {
	steps {
		sayHello('joost')
	}
    }
  }
}
