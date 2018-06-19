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
                    sh 'cd gradle-site-plugin'
                    sh 'gradlew build'
                    
                }
            }
        }
        
    }
}
