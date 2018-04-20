pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh 'ansible-playbook -i hosts -s -u user_name site.yml --ask-sudo-pass'
      }
    }
  }
}