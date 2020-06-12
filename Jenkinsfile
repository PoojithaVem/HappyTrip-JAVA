node{
    stage('SCM Checkout'){
      git 'https://github.com/PoojithaVem/HappyTrip-JAVA'
    }
    
    stage('Compile checkout'){
      def mvnHome = tool name: 'maven_3.6.0', type: 'maven'
      sh "${mvnHome}/bin/mvn package"    
    }
}
