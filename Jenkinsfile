pipeline{
	agent any
	stages{
		stage('build'){
			steps {
				echo 'building project..'
				npm install
			}
		}
		stage('deploy'){
			steps {
				npm start
			}
		}
	}
}
