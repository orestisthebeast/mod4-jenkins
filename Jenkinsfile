pipeline {
    agent any
    stages {
        stage('Pipeline stages') {
            steps {
                script {
                    sh '''
                    echo "Sup"
                    pwd
                    whoami
                    '''
                }
            }
        }
        stage('Second stage') {
            steps {
                script {
                    sh '''
                    touch 1.txt
                    echo "I am inside the text file!" > 1.txt
                    cat 1.txt
                    rm 1.txt
                    '''
                }
            }
        }
    }
}