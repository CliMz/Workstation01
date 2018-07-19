pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'Hello'
        sh '''#!/bin/bash
echo "What"'''
        input(message: 'Sure ?', ok: 'ok')
      }
    }
  }
}