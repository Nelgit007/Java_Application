@Library('Jenkins_Shared_Library') _

pipeline{

    agent any

    parameters{

        choice(name: 'actions', choices: 'create\ndelete', description: 'Choose create/Destroy')
    }

    stages{
        
        stage('Git Checkout'){

            steps{
            gitCheckout(

                branch: "main",
                url: "https://github.com/Nelgit007/Java_Application.git"
            )
            }
        }
        // stage('Unit test using maven'){

        //     when { expression {  params.action == 'create' } }
        //     steps{
        //         script{

        //             mvnTest()
        //         }
        
        //     }
        // }
        // stage('Integration test using maven'){

        //     when { expression {  params.action == 'create' } }
        //     steps{
        //         script{

        //             mvnIntegrationTest()
        //         }
        
        //     }
        // }
    }
}