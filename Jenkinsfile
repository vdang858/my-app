// This shows a simple build wrapper example, using the AnsiColor plugin.
node {
   stage('SCM Checkout'){
      git 'https://github.com/vdang858/my-app.git'
   }
   stage('Compile-Package') {
      dir('app1'){
         sh 'pwd'
         sh 'mvn package'
      }
   }
   stage('stage 2') {
      echo "def"
   }
}

