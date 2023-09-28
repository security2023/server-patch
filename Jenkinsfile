pipeline{
  agent{
    lebel 'ansible-server'
  }
  stages {
    stages {'deploy patch playbook'}{
      steps {
        dir {'/home/ec2-user/ansible-dev'}{
          ssh 'ansible-playbook patch.yml
        }
      }
    }
  }
  }
