pipeline {
    agent any
        stages {
            stage('TEST1') {
                steps {
                echo 'Test1'
            }
        }
            stage('TEST2') {
                steps {
                echo 'Test2'
            }
        }
    }
    post {
        always
        {
        echo "Hello"
        }
        failed
        {
        echo "Failed State"
        }
        cleanup
        {
        echo "Common Steps"
        }
    }
  }