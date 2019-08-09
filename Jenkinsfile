node {
    stage('Example') {
        echo env.BRANCH_NAME
        checkout scm
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute elsewhere'
        }
    }
}
