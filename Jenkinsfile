pipeline {
	agent any   
	triggers { 
		pollSCM('H/4 * * * *') 
	}
    stages {
        stage("unit test") {
            steps {
                echo 'unit test'
            }
        }
    }
}
