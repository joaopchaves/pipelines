node("windows-agent") {
    stages {
        stage('Hello') {
            steps {
                bat 'echo Hello world'
                echo "Build number is ${currentBuild.number}"
            }
        }
    }
}