// This shows a simple build wrapper example, using the AnsiColor plugin.
node {
   stage('SCM Checkout'){
      git 'https://github.com/vdang858/my-app.git'
   }
   stage('Compile-Package') {
      dir('app1'){
         //sh 'mvn package'
         def mvnHome = tool name: 'maven-3', type: 'maven'
         sh "${mvnHome}/bin/mvn package"
      }
   }
   stage('stage 2') {
      echo "def"
   }
}

