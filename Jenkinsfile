pipeline {
    agent any
    tools {
      gradle 'Gradle-7.3-mil3'
}
    stages {
        stage('build') {
            steps {
                echo 'building the application'
                sh './gradlew -v'
            }
        }
        stage('test') {
            steps {
                echo 'testing the application'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying the application'
            }
        }
    }
}
