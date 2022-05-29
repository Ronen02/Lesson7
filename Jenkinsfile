properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git "https://github.com/Ronen02/Lesson7.git"
    }
    stage("show files"){
        sh "ls -l"
    }
}
