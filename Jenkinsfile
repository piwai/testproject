#!/usr/bin/env groovy

//@Library("testlib@v0.1")

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
