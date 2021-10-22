pipeline {
    agent any
   stages {
        stage('Verify Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
       stage('build') {
           steps {
           sh "mvn clean install -DskipTest"
                }
           }
    }
}
