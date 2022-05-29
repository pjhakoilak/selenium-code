pipeline{
    
    agent any
    
    stages{
        
        
        stage("build"){
            steps{
                echo("Build the project")
            }
        }
        
        stage("Run my UT's"){
            steps{
                echo("Running Unit level cases")
            }
        }
        
        stage("Deployed to QA"){
            steps{
                echo("Deploying to QA")
            }
        }
        
        stage("Run my automation cases"){
            steps{
                echo("Running automation cases")
            }
        }
        
        stage("Deploy to stage"){
            steps{
                echo("Deploying to stage")
            }
        }
        
        stage("sanity on stage"){
            steps{
                echo("Sanity on stage")
            }
        }
        
        stage("Deploye on production"){
            steps{
                echo("Deploying to Prouction")
            }
        }
        
    }
    
}