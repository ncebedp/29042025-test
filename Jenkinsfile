pipeline{
    agent any
    stages{
        stage("Stage 1"){
            steps{
                echo 'Welcome to first declarative pipeline';
                sh 'whoami';
                sh "apt install sudo -y";
                sh 'sudo apt update -y';
            }
        }
    }
     
}