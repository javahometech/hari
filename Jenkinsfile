node {
    stage('Example') {
        checkout scm
        sh "git branch | grep \* | cut -d ' ' -f2"
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute elsewhere'
        }
    }
}
