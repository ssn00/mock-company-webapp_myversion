pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */

      agent any
    stages { 
        stage('Build') {
            steps {
              echo ./gradlew aseemble
            }
        }

      stage('Test') {
            steps {
              echo ./gradlew test
            }
        }
    }
}
