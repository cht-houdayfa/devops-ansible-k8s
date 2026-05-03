pipeline {
  agent any
  stages {
    stage('Deploy to Kubernetes') {
      steps {
        sh '''
          cd ansible
          ansible-playbook k8s-nginx-ansible.yml
        '''
      }
    }
  }
}
