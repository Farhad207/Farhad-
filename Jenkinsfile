node{
   stage('SCM Checkout'){
     git 'https://github.com/Farhad207/Farhad-.git'
   }
   stage('Compile-Package'){
      // Get maven home path
     // def mvnHome =  tool name: 'maven', type: 'maven'   
      sh mvn package"
   }

}
