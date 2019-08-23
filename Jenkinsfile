node{
   stage('SCM Checkout'){
      git 'https://github.com/Pankajsingh63/cicd'
   }
   stage('Compile-Package'){
    def mvnHOME= tool name: 'Maven', type: 'maven'
      sh "${mvnHOME}/bin/mvn package"
   }
 }
