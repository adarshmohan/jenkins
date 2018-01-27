node {
  stage ('scm-checkout') {
  checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'file:///E:\\Training\\Devops\\helloworldweb-master\\helloworldweb-master']]])
  }
  
  stage (build") {
bat 'C:\\Users\\Adarsh\\apache-maven-3.5.2\\bin\\mvn clean package'
         }
         
         stage ('archive') {         
archiveArtifacts 'target/Helloworldwebapp.war'
         }
}


