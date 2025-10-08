pipeline{
	agent any
	stages{
		stage("Cloning repo"){
			steps{
				echo "Repo is cloned successfully" 
			}
		}
		stage("Program execution"){
			steps{
				sh 'java sample.java'
			}
		}
	}
}
