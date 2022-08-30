pipeline {
	agent any 
		stages{
			stage('1-clone repo'){
				steps{
				sh  'echo "walk."'
				}
			}
			stage('2-run victoria script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/victoria.sh'
        }
			}
			stage('3-run daniel script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/daniel.sh
				}
			}
			stage('4-run temi script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/temi.sh
        }
			}
      stage('5-run frank script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/frank.sh
        }
	}
	stage('6-run sukhman script'){
				steps{
					sh 'bash -x /var/lib/jenkins/project7/sukhman.sh

        }
      }
    }
}
