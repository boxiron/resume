pipeline {
    agent any

    environment {
        BRANCH_NAME ='main'
        GIT_URL = 'https://github.com/boxiron/resume.git'
    }

stages {
 stage('git checkout'){
    steps{
        git branch: "${BRANCH_NAME}", url: git branch: 'main', url: "${GIT_URL}"
    }
 }
 stage('docker build'){
    steps{
        sh 'docker build -t resume .'
        sh 'docker images'
    }
 }
}


}