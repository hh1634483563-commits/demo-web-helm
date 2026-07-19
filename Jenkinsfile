pipeline {
  agent any 
  stages {
    stage('Checkout') {
      steps {
        echo '代码已拉取'
      }
    }
    stage ('Build'){
      steps {
        echo '开始构建'
      }
    }
    stage('Test') {
      steps {
        echo '开始测试'
      }
    }
  }
  postP{
    success{
      echo 'Pineline执行成功'
    }
  }
}
