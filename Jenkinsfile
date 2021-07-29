pipeline
{
agent any

stages {
     stage('Build Application'){
steps {
     bat 'mvn clean install'
     }
   }
stage ('Test'){
     steps {
          bat 'mvn package deploy -DmuleDeploy'
}
}
stage ('Deploy'){
     steps {
          bat 'mvn package deploy -DmuleDeploy'
}
}
}
}
