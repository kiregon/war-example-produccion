pipeline {
	agent any

  environment {
		VERSION = '0.0.1'
	}

	stages {
		stage('Deploy') {
			steps {
        // wget o curl
				bat 'copy C:\\Users\\J11713\\.m2\\repository\\bootcamp\\jenkins\\war-example\\' + env.VERSION + '\\war-example-' + env.VERSION + '.war C:\\devenv\\ambientes\\tomcat1\\apache-tomcat-9.0.96\\webapps\\ROOT.war'
			}
		}
	}
}
