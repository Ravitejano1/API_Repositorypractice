  pipeline {                    
      agent any
         stages {
              stage('Clone repo'){
                steps{
                      git branch: 'main', credentialsId: 'GitHubcred', url: 'https://github.com/Ravitejano1/API_Repositorypractice.git'
                }
              }
              stage('Maven Build'){
                steps{
                         sh "mvn clean package"
                }
            }
        }
  }
