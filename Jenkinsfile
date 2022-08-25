pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh 'curl -f -k -H \'Content-Type: application/json\' -XPOST --user admin:password http://192.168.56.62/api/v2/job_templates/ping/launch/'
      }
    }

  }
}