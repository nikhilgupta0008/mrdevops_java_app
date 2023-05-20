@Library('my-shared-Library') _

pipeline{

    agent any

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