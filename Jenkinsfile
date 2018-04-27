#!groovey
node("jenkins-slave1"){
	stage('checkout')
	{
	def workspace = "/home/jenkins/newworkspace"
	git branch: 'first', url: 'https://github.com/srijb/first.git', credentialsId: 'jenkins'
	}
			}
