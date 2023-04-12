pipeline{

    agent any

    stages{

        stage('Git Checkout'){

            steps{

                script{

                    git branch: 'main', url: 'https://github.com/Lubern5/mrfig_java_app'
                }
            }
        }
    }
}