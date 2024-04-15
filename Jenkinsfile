pipeline {
    agent any
    stages {
        stage('Greeting Datascientest') {
            steps {
                echo 'Hello Datascientest'
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
