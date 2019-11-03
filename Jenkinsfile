
node {
	stage('SCM chckout'){
		git 'https://github.com/yashwantpawar/my-app'
	}
	stage('Compile and package'){
		sh 'mvn package'	
	}
}

