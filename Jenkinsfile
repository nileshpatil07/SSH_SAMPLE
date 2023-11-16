#!/usr/bin/groovy
@Library('sshDeploy') _

node {
  checkout scm
    sshDeploy('deploy.yml', false)
    //sshDeploy('deployment.yml');
}
