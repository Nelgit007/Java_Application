@Lirary('Jenkins_Shared_Library') _

pipeline{

    agent any

    stages{
        
        stage('Git Checkout'){

            steps{

                script{

                    gitCheckout(

                        branch: "main"
                        url: "https://github.com/Nelgit007/Java_Application.git"
                    )
                }
            }
        }
    }
}