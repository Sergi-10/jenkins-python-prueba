pipeline {
    agent any

    stages {
        stage('Clonar repositorio') {
            steps {
                git credentialsId: 'github-token',
                    url: 'https://github.com/Sergi-10/jenkins-python-prueba.git'
            }
        }
    }
}
