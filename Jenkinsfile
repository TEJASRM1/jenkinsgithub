pipeline {
    agent none
    stages {

    parallel {
       stage('one') {
           steps {
	   agent{label 'labelone'}
           echo 'Hello label ONE'
            }
        }
     }

        stage('one') {
           steps {
	   agent{label 'labelone'}
           echo 'Hello label ONE'
            }
        }
     }

   }


