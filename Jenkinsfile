pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Hello from JENKINS-64719-b\n${scm}\n${scm.userRemoteConfig[0]}"
                checkout scm
            }
        }
    }
}
