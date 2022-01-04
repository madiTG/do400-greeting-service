pipeline{
    agent{
        label "nodejs"
    }
    stages{
        stage("Install dependencies"){
            steps{
                sh "npm ci"
            }
        }

        stage("Check Style"){
            steps{
                sh "npm ci"
            }
        }

        stage("Test"){
            steps{
                sh "npm test"
            }
        }

        // Add the "Deploy" stage here
    }
}
