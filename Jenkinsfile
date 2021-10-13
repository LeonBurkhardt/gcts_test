@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
        gctsExecuteABAPUnitTests script:this
    }
}
