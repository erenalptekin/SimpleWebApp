node {
   stage('Preparation') {
      git 'https://github.com/erenalptekin/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}