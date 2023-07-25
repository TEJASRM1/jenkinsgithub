pipeline {
    agent none

    stages {
        stage('one') {
            steps {
                agent{label 'labelone'}
                echo 'label ONE'
            }
        }

        stage('two') {
            steps {
                agent{label 'labeltwo'}
                echo 'label TWO'
            }
        }
    }
}
