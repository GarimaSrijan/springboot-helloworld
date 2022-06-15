pipeline {
    agent any 
    stages {
        stage('Hello') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
