@Library('utils@master') _

// PRs only: SonarQube Analysis, in a pod of its own (podCI.sonar).
if (env.CHANGE_ID) {
  stage('SonarQube Analysis') {
    podCI.sonar(sonarScanner: 'sonar', projectKey: 'Instabug_teamwork_AYtHdSxj7vrPPoHUPcJ3')
  }
}
