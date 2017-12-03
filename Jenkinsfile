pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''node /test/api.test.js
node /test/browser.test.js
node /test/helpers.test.js
node /test/testHelpers.js
node /test/users.test.js'''
      }
    }
  }
}