pipeline {
    agent { label 'docker-agent2' } 
    stages {
        stage('Clone source code') {
            steps {
                git branch: 'main', url: 'https://github.com/mranh1610/demo-jenkins3.git'
            }
        }
    }
}
