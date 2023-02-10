pipeline {
  agent {
    kubernetes {
        label "jenkins-slave"
    }
  }
 
  stages{
        stage('测试'){
            steps {
                sh """
                    echo hello
                   """
            }
        }
  }
}
