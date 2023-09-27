pipeline{
 	agent any 
 	stages{
 		stage('1-clonecode'){
 			steps{
 				sh checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'team7-git-id', url: 'https://github.com/Kondji237/team7jenkinsapp.git']])
 			}
 		}
 		stage('2-artifactbuild'){
 			steps{
 				sh 'df -h'
 			}
 		}
 		stage('3-unitest'){
 			steps{
 				sh 'lscpu'
 			}
 		}
 	}
 }
