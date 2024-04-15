pipeline {
    agent any
    stages {
        stage('Greeting Datascientest') {
            steps {
                // Steps here
            }
        }
    }
    post {
        always {
            echo "Pipeline finished Greeting datascientest"
            sh "./datascientest-clean.sh"
        }
    }
}
