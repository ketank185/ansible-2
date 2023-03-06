pipeline {
	agent {
		label {
			label "built-in"
			customWorkspace "/opt/mayu"
			}
	}
	stages {
		stage ("clean workspace"){
			steps {
			cleanWs()
			}
		}
		stage ("checkout code from git") {
			steps {
			 	checkout scm
			}
		}
		
	}	
}
