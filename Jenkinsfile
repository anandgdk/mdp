pipeline{
    agent any
      satges{
        stage("maven build"){
            when{
            branch `develop`
            }
          steps{
            echo "hi jenkins.."
            }
           }
         }
     }
