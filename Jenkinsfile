@Library('shared-lib') _

pipeline {
    agent any

    stages {
        stage('Run Common Build') {
            steps {
                commonBuild()
            }
        }
    }
}
