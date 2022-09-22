pipeline {
  agent any
  stages {
    stage('requirements') {
      steps {
        sh 'gem install bundler -v 2.3.7'
      }
    }
    stage('build') {
      steps {
        echo 'process start'
        sh 'bundle install'
        sh 'rails db:migrate'
        echo 'process end'
      }
    }
    // stage('test') {
    //   steps {
    //     sh 'rake'
    //   }
    // }
  }
}
