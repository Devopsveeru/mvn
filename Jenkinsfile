pipeline{
  agent any
  stages{
    stage("Git Checkout"){
      steps{
            git url: 'https://github.com/Devopsveeru/tata.git'
           }
    }
    stage("Maven Build"){
       steps{
            sh "mvn clean install"
            sh "mv target/*.war target/mcs.war"
     
            }
    }
  }
}
