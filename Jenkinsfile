pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Anagha"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Hello Pradyumna Kodgi"'
              
            }
        }
    }
}
