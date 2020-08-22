pipeline {
    agent any
    tools {
        maven 'Maven_3.6.3_1'
    }
    stages {
        stage ('Compile Stage') {

            steps {
                    sh 'mvn clean package'
            }
        }
    }
}
