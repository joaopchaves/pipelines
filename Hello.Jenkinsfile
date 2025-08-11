node("windows-agent") {
    stages{
        stage('Hello'){
            steps{
                sh 'echo Hello word'
                echo "Build number is ${currentBuild.number}"
            }
        }
    }
}