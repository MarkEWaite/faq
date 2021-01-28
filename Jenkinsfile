pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo """"
Hello from JENKINS-64719-b
${scm}
${scm.userRemoteConfigs[0]}
                """
                checkout scm
            }
        }
    }
}
