def CUSTOM_WORKSPACE="/tmp/jenkins/workingDir001"

node  {
    checkout scm

    stage "initialise" {
        sh "echo checking for ${CUSTOM_WORKSPACE}"
    }

    stage "building" {
        sh "echo building"    
    }
    

    stage "executing" {
        sh "echo executing for workspace : ${env.WORKSPACE}"
    }
    if ( 1 > 0 ) { 
        sh 'echo hello'
    }
}