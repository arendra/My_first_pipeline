pipeline{
	agent any
	def nodeHome="/root/node-v6.3.1-linux-x64"
	echo ${nodeHome}
	env.PATH="${nodeHome}/bin:${env.PATH}"
	stages{
		stage('build'){
			steps {
				echo 'building project..'
				// sh 'export PATH=$PATH:/root/node-v6.3.1-linux-x64/bin'
				sh 'npm install'
			}
		}
		stage('deploy'){
			steps {
				sh 'npm start'
			}
		}
	}
}
