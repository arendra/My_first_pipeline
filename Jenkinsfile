pipeline{
	agent any
	stages{
		stage('build'){
			steps {
				echo 'building project..'
				sh 'export PATH=$PATH:/root/node-v6.3.1-linux-x64/bin'
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
