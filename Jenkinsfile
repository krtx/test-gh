def commit_id

pipeline {
  agent any
  stages {
    stage("checkout") {
      steps {
        step {
          commit_id = checkout(scm).COMMIT_ID
          echo "commit_id: ${commit_id}"
        }
      }
    }
  }
}
