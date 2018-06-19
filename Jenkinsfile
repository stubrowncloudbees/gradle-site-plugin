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
                    sh 'cd gradle-site-plugi*'
                    sh 'gradlew build'
                    
                    
                }
            }
        }
        
    }
}
