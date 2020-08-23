pipeline {
    agent any
    tools {
        maven 'localmaven'
    }
    tools {
        docker 'docker'
    }
    stages {
        stage ('Compile Stage') {

            steps {
                    sh 'mvn clean package'
                    sh 'docker build . -t tomcatweb:${env.BUILD_ID}'
            }
        }
    }
}
