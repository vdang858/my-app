// This shows a simple build wrapper example, using the AnsiColor plugin.
node {
   stage('Send email'){
      build.previousBuild.result.toString().equals('FAILURE')
   }
   stage('SCM Checkout'){
      git 'https://github.com/vdang858/my-app.git'
   }
   stage('Compile-Package') {
      dir('app1'){
         sh 'mvn package'
      }
   }
   stage('stage 2') {
      echo "def"
   }
}

