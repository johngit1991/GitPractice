@Library('MySharedLibrary') _

pipeline {
    agent any

    stages {
        stage('Upload Artifacts') {
            steps {
                script {
                    uploadArtifacts('/home/osboxes/jenkinslib/source', '/home/osboxes/jenkinslib/destination')
                }
            }
        }
    }
}
