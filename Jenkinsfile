pipeline {
    agent any
    tools {
        maven 'localmaven'
    }
    stages {
        stage ('Compile Stage') {

            steps {
                    sh 'mvn clean package'
            }
        }
    }
}
