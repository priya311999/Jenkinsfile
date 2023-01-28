pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('First Application') { 
            steps { 
                echo "First"
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
