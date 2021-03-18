#!/usr/bin/env groovy

@Library("testlib@v0.1") _

pipeline {
	agent { node { label 'master' } }

	stages {
  		stage("test") {
			steps {
     				sh "echo 'It works!'"
			}
  		}
	}
}
