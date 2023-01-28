pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('First') { 
            steps { 
                echo "First App"
            }
        }
        stage('Second'){
            steps {
                echo "Second"
            }
        }
        stage('Third') {
            steps {
               echo "Third"
            }
        }
         stage('Fourth') {
            steps {
               echo "Fourth"
            }
        }
    }
}
