def commit_id

pipeline {
  agent any
  stages {
    stage("checkout") {
      steps {
        script {
          commit_id = checkout(scm).GIT_COMMIT
          echo "commit_id: ${commit_id}"
          echo "checkout: ${checkout(scm)}"
        }
      }
    }
  }
}
