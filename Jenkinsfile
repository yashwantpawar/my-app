
node {
	stage('SCM chckout'){
		git 'https://github.com/yashwantpawar/my-app'
	}
	stage('Compile and package'){
		// get maven home path
		def mvnHome=tool name: 'maven', type: 'maven'
		sh "${mvnHome}/bin/mvn package"	
	}
}

