pipeline {
    agent none
    stages {

stage("parallelpipe")
{
    parallel {
       stage("one") {
	    agent{label 'labelone'}
            steps {
                echo 'Hello label ONE'
            }
        }
     }

        stage("two") {
	    agent{label 'labeltwo'}
            steps {
                echo 'Hello label TWO'
            }
        }
     }
   }

   }
