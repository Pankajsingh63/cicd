node{
   stage('SCM Checkout'){
      tool name: 'Maven', type: 'maven'
     git 'https://github.com/Pankajsingh63/cicd'
   }
   stage('Compile-Package'){
    sh 'mvn package'
   }
 }
