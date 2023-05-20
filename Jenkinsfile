@Library('my-shared-library') _

pipeline{

    agent any
    options {
        skipDefaultCheckout false
    }

    stages{

        stage('Git Checkout'){

            steps{

                script{

                    gitCheckout(
                        branch: "main",
                        url: "https://github.com/nikhilgupta0008/mrdevops_java_app.git"
                    )
                    
                }
            }
        }
    }
}