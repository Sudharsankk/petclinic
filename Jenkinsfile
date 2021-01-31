pipeline    {
    agent any
// { label 'Node-Name' }   //
    stages  {
        stage('Git-Checkout')   {
            steps   {
                echo "Checking out from Git repo";
                git 'https://github.com/Sudharsankk/petclinic.git'
            }
        }
        stage('Maven-Build')   {
            steps   {
                echo "Building the checked-out project";
            }
         }
        stage('Unit Test')   {
            steps   {
                echo "Unit Test is being done on the build"
            }
          }
        stage('Deploy')   {
            steps   {
                echo "Deploying the artifact to repository"
            }
        }
        stage('Deployment Validation')   {
            steps   {
                echo "Verifying Deployment status "
            }
         }

    }
}
