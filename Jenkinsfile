node {
  git url: 'https://github.com/PoojithaVem/HappyTrip-JAVA.git'
  def mvnHome = tool name: 'maven_3.6.0', type: 'maven'
  sh '''
          cd happytrip-code
          mvn clean install
          ${mvnHome}/bin/mvn -B verify
    '''

}
