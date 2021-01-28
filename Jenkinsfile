pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo """"
Hello from JENKINS-64719-b
scm: ${scm}
branches: ${scm.branches}
userRemoteConfigs[0]: ${scm.userRemoteConfigs[0]}
                """
                // checkout scm
            }
        }
    }
}
