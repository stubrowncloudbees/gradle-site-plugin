pipeline {
    agent {
        node {
            label 'gradle'
            }
        }
    stages {
        stage('build') {
            steps {
                container('gradle') {
                    sh 'id'
                    sh 'ls'
                    sh './gradlew build'
                    
                    
                }
            }
        }
        
    }
}
