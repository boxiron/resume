pipeline {
    agent any

stages {
 stage('git checkout'){
    steps{
        git branch: 'main', url: git branch: 'main', url: 'https://github.com/boxiron/resume.git'
    }
 }
 stage('test'){
    steps{
        sh 'echo test'
    }
 }
}


}