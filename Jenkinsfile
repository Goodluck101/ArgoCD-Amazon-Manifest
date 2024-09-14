node {
    def app
    
    env.IMAGE = 'goodluck101/amazon'

    stage('Clone repository') {
             git branch: 'main', url: 'https://github.com/Goodluck101/ArgoCD-Amazon-Manifest.git'  
    }

    stage('Update GIT') {
            script {
                catchError(buildResult: 'SUCCESS', stageResult: 'FAILURE') {
                    withCredentials([usernamePassword(credentialsId: 'Senior-DevOps-Teaam', passwordVariable: 'GIT_PASSWORD', usernameVariable: 'GIT_USERNAME')]) {
                        //script {def encodedPassword = URLEncoder.encode("$GIT_PASSWORD",'UTF-8')}
                        //script  {def IMAGE='goodluck101/amazon'}
                        sh "git config user.email ekeomaadiole@gmail.com"
                        sh "git config user.name Goodluck101"
                        //sh "git switch master"
                        sh "cat deployment.yml"
                        sh "sed -i 's+${IMAGE}.*+${IMAGE}:${DOCKERTAG}+g' deployment.yml"
                        sh "cat deployment.yml"
                        sh "git add ."
                        sh "git commit -m 'Done by Jenkins Job changemanifest: ${env.BUILD_NUMBER}'"
                        sh "git push https://${GIT_USERNAME}:${GIT_PASSWORD}@github.com/${GIT_USERNAME}/ArgoCD-Amazon-Manifest.git HEAD:main"
             }
         }
     }
  }
}
