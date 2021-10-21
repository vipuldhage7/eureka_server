pipeline {
    agent any
    tools{
        maven 'maven 3.13'
        jdk 'jdk8'
    }
    stages {
        stage('Verify Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
    }
}
