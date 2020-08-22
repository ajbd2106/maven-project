pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'mvn') {
                    sh 'mvn clean package'
                }
            }
        }
    }
}
