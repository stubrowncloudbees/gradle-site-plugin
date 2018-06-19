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
                    sh 'ls -lart'
                    sh 'sleep 5'
                    sh 'cd gradle-site-plugin'
                    sh 'gradlew build'
                    
                }
            }
        }
        
    }
}
