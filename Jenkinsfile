pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('First') { 
            steps { 
                echo "First Application"
            }
        }
        stage('Second'){
            steps {
                echo "Second Application"
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
