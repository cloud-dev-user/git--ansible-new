pipeline {
  agent any
  stages {
    stage('Run playbook') {
      steps {
        sh ' ansible-playbook tomcat_install.yaml'
      }
    }

  }
}
