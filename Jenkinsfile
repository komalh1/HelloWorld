pipeline {
    agent any
    environment {

        NEW_VERSION = '1.3.0'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo "Building version ${NEW_VERSION}"
                echo "Building on Build ${BUILD_ID}"
                echo "Building on Build $(BUILD_DISPLAY_NAME)"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
