node{

                 stage('Clone repo'){
                 git branch: 'main', url: 'https://github.com/Ravitejano1/API_Repositorypractice.git'
                }

                stage('Maven Build'){
                def mavenHome = tool name: "MAVEN_HOME", type: "maven"
                def mavenCMD = "${mavenHome}/bin/mvn"
                sh "${mavenCMD} clean package"
                }
}
