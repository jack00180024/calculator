pipeline {
	agent any   
	triggers { 
		pollSCM('H/2 * * * *') 
	}
    stages {
        stage("unit test") {
            steps {
                echo 'unit test'
            }
        }
    }
}
