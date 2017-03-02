pipeline{
	agent any
	stages{
		stage('build'){
			steps {
				echo 'building project..'
				sh '/root/node-v6.3.1-linux-x64/bin/npm install'
			}
		}
		stage('deploy'){
			steps {
				sh '/root/node-v6.3.1-linux-x64/bin/npm start'
			}
		}
	}
}
