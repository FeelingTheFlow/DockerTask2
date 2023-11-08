pipeline {
  agent { dockerfile true }
    stages {
        stage('Testing server') {
            steps {
                echo "Testing.."
                sh './test.sh'
            }
        }
	

    }
}
