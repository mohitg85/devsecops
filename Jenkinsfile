pipeline {
  agent any
  stages {
    stage('Pulling Repo') {
      agent any
      steps {
        git(poll: true, url: 'https://github.com/mohitg85/Devsecops.git', changelog: true)
      }
    }

  }
}