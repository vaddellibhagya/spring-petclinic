pipeline {
    agent any
    stages {
        stage ('test') {
            steps {
                sh 'echo hello'
            }
        }
        stage ("learning") {
            steps {
                git branch: 'main',url:'https://github.com/vaddellibhagya/spring-petclinic'
            }
        }
    }
}
