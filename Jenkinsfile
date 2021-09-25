properties([pipelineTriggers([pollSCM('30 * * * *')])])
node {
    stage("clone"){
        git branch: 'master', url: 'https://github.com/iliava/MySoftware.git'
    }
    stage("time"){
        bat "time /t"
    }
}
