pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat 'mvn -B -DskipTests -Denforcer.skip=true clean package' 
            }
        }
    }
}
