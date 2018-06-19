pipeline {
    agent {
        node {
            label 'gradle'
            }
        }
    stages {
        stage('build') {
            steps {
                container('maven') {
                    sh 'cd gradle-site-plugin'
                    sh 'gradlew build'
                    
                }
            }
        }
        
    }
}
