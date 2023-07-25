pipeline {
    agent none
    stages {

    parallel {
       stage('stageone') {
	    agent{label 'labelone'}
            steps {
                echo 'Hello label ONE'
            }
        }
     }

        stage('stagetwo') {
	    agent{label 'labeltwo'}
            steps {
                echo 'Hello label TWO'
            }
        }
     }

   }
}

