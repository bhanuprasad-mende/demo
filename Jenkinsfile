pipeline {
  agent any
  stages {
    // stage('requirements') {
    //   steps {
    //     sh 'gem install bundler -v 2.3.7'
    //   }
    // }
    stage('build') {
      steps {
        sh 'bundle install'
      }
    }
    // stage('test') {
    //   steps {
    //     sh 'rake'
    //   }
    // }
  }
}
