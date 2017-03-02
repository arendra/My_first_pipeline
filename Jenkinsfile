pipeline{
	agent any
	stages{
		stage('build'){
			steps {
				echo 'building project..'
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
