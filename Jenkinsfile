pipeline {
    agent none
    stages {

stage("parallelpipe")
{
    parallel {
       stage("one") {
	    agent{label 'label1'}
            steps {
                echo 'Hello label ONE'
            }
        }
     

        stage("two") {
	    agent{label 'label2'}
            steps {
                echo 'Hello label TWO'
            }
        }
       
         stage("three") {
	    agent{label 'label3'}
            steps {
                echo 'Hello label THREE'
            }
        }
     }
   }
}
}
