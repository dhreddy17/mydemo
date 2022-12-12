node {
    stage('checkout') {
      git branch: 'main', url: 'https://github.com/dhreddy17/mydemo.git'
    }
    stage('build') {
      sh 'mvn clean install package'
    }
   }
