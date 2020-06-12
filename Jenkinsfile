node{
    stage('SCM Checkout'){
      git 'https://github.com/PoojithaVem/HappyTrip-JAVA/blob/master/happytrip-code/pom.xml'
    }
    
    stage('Compile checkout'){
      def mvnHome = tool name: 'maven_3.6.0', type: 'maven'
      sh "${mvnHome}/bin/mvn package"    
    }
}
