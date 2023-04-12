@Library('my-shared-library')

pipeline{

    agent any

    stages{

        stage('Git Checkout'){

            steps{

                script{

                    gitCheckout(
                        branch: "main"
                        url: "https://github.com/Lubern5/mrfig_java_app"
                    )
                }
            }
        }
    }
}