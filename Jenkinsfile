node {
   stage('Preparation') {
      git 'https://github.com/erenalptekin/SimpleWebApp.git'
   }
   stage('Build') {
      bat "./gradlew clean test"
   }
}