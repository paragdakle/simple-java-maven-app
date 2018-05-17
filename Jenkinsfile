pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh '/work/pdakle/mvn -B  clean verify' 
            }
        }
    }
}
