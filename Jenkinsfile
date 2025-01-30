pipeline{
    agent any
    stages{
        stage('Pipeline stages'){
            steps {
            """
            echo "Sup"
            pwd
            whoami
            """
            }
        }
        stage('Second stage'){
            steps {
            """
            touch 1.txt
            echo "echo I am inside the text file!" > 1.txt
            cat 1.txt
            rm 1.txt
            
            """
            }
        }
    }
}