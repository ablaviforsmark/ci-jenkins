pipeline{
    agent any
   /* tools{
        maven “maven3”
    }
    environment {
        NEXUS_VERSION =
        NEXUS_REPO =
        NEXUS_URL =
        NEXUS_CREDENTIAL_ID
    }
   */
   stages{
       stage('Fetch code'){
           steps{
               git branch: 'Jpac',
               url: 'https://github.com/ablaviforsmark/ci-jenkins.git'
            }
       }
   }
}
