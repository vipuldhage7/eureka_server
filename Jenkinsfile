pipeline {
    agent any
    tools{
        maven 'Maven 3.3.9'
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
