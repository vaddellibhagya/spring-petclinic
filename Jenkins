pipeline {
    agent any
    stages {
        stage('test') {
            step {
                sh 'echo hello'
            }
        }
        stage ("learning") {
            steps{
                git branch: 'master',url:'https://github.com/vaddellibhagya/spring-petclinic'
            }
        }
    }
}
