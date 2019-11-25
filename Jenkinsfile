pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
               def mvn_version = 'M3'
               withEnv( ["PATH+MAVEN=${tool mvn_version}/bin"] ) {
               sh "mvn clean package"
}
            }
        }
        }
        //stage('--test--') {
           // steps {
              //  sh "mvn test"
          //  }
       // }
       // stage('--package--') {
          //  steps {
            //    sh "mvn package"
          //  }
       // }
  //  }
//}
