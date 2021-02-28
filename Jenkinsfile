pipeline
{
agent any

stages {
     stage('Build Application'){
steps {
     bat 'mvn clean install'
     }
   }
stage ('Deploy'){
     steps {
          bat 'mvn package deploy -DmuleDeploy'
}
}
stage ('Test'){
     steps {
          bat 'mvn package deploy -DmuleDeploy'
}
}