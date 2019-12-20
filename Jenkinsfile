node{
stage('SCM Checkout'){

git 'https://github.com/arpitha1993/arpu'
}
stage('Compile-Package'){
  // Get maven home path
   def mvnHome = tool name: 'mt maven', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}

}
