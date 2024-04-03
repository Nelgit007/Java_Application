@Library('Jenkins_Shared_Library') _

pipeline{

    agent any

    stages{
        
        stage('Git Checkout'){

            steps{
            gitCheckout(

                branch: "main"
                url: "https://github.com/Nelgit007/Java_Application.git"
            )
            }
        }
    }
}