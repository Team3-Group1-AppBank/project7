pipeline {
	agent any 
		stages{
			stage('1-clone repo'){
				steps{
				checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'team3hook', url: 'https://github.com/Team3-Group1-AppBank/project7.git']]])
				}
			}
			stage('2-run victoria script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/victoria.sh'
				}
			}
			stage('3-run daniel script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/daniel.sh'
				}
			}
			stage('4-run temi script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/temi.sh'
				}
			}
      			stage('5-run frank script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/frank.sh'
			}
			 	}
	           stage('6-run sukhman script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/sukhman.sh'
       				}
      		   	}
			 stage('7-run joe script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/joe.sh'
       				}
      			}
			stage('8-run gloria script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/nana.sh'
       				}
      			}
			stage('9-run kingsley script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/kingsley.sh'
       				}
      			}
			
    		}
	}
