pipeline{
	agent any
	stages{
		stage('build'){
			echo 'building project..'
			npm install
		}
		stage('deploy'){
			npm start
		}
	}
}
