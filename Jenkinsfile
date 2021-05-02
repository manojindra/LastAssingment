pipeline {
    agent any
    stages {
        stage('Git Clone') {
            steps {
                git branch: 'main', credentialsId: '8ac4dfc1-1252-4151-891e-2c970acc19a2', url: 'https://github.com/manojindra/LastAssingment'
            }
        }
    }
}
