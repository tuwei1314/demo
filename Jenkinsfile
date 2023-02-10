pipeline {
  agent {
    kubernetes {
        label "jenkins-slave"
        yaml """
kind: Pod
metadata:
  name: jenkins-slave
spec:
  containers:
  - name: jnlp
    image: "jenkins/inbound-agent:4.10-3-jdk8"
"""
    }
  }
 
    stages {
        stage('测试'){
            steps {
                sh """
                    echo hello
                   """
            }
        }
　　}
}