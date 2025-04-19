pipeline {
  agent any

  stages {
    stage('Cloning my git hub repo') {
      steps {
        echo 'It's already cloned'
      }
    }

    stage('runing script') {
      steps {
        sh 'chmod +x Hello_script.sh && ./Hello_script.sh'
      }
    }
  }
}
