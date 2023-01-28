  pipeline {                    
      agent any
         stages {
              stage('git'){
                steps{
                      git branch: 'main', credentialsId: 'GitHubcred', url: 'https://github.com/Ravitejano1/API_Repositorypractice.git'
                }
              }
              stage('Build'){
                steps{
                         bat 'mvn validate'
                }
            }
        }
  }
