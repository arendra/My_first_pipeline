// pipeline{
//	agent any
//	environment {
//		def nodeHome="/root/node-v6.3.1-linux-x64"
//		// echo ${nodeHome}
//		env.PATH="${nodeHome}/bin:${env.PATH}"
//	}
//	stages{
//		stage('build'){
//			steps {
//				echo 'building project..'
//				// sh 'export PATH=$PATH:/root/node-v6.3.1-linux-x64/bin'
//				sh 'npm install'
//			}
//		}
//		stage('deploy'){
//			steps {
//				sh 'npm start'
//			}
//		}
//	}
// }
// stages {
stage 'build'
node{
	def nodeHome="/root/node-v6.3.1-linux-x64"
//	echo ${nodeHome}
	env.PATH="${nodeHome}/bin:${env.PATH}"
	echo "Building nodejs code..."
	sh 'npm install'
}

// stage 'deploy'
// node{
//	def nodeHome="/root/node-v6.3.1-linux-x64"
//        echo ${nodeHome}
//        env.PATH="${nodeHome}/bin:${env.PATH}"
//        echo "Deploying nodejs code..."
//        sh 'npm start'
// }
// }
