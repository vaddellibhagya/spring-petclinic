node('OPENJDK-11-JAVA') {
    stage('vcs') {
        git branch: 'main', url: 'https://github.com/GitPracticeRepo/spring-petclinic.git'
    }
    stage("build") {
        sh '/usr/share/maven/bin/mvn package'
    }
    stage("archive results") {
        junit '**/surefire-reports/*.xml'

    }
}
