def commit_id

pipeline {
  agent any
  stages {
    stage("checkout") {
      steps {
        commit_id = checkout(scm).COMMIT_ID
        echo "commit_id: ${commit_id}"
      }
    }
  }
}
