
Pipeline {
          agent { docker { image 'maven:3.3.3'} }
	stage {
		stage('build') {
		      steps {
			     sh 'mvn  --version'
			      echo 'Hello World'
			      echo 'Hello'
			}
		}
	}
}
