pipeline{
    agent any
    stages{
        stage("Stage 1"){
            steps{
                echo 'Welcome to first declarative pipeline';
                sh 'whoami';
                sh 'apt update -y && apt upgrade -y';
                sh "apt install sudo -y";
            }
        }
    }
     
}