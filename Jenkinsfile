pipeline {
   
   stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
   }
   
   triggers {
       // poll repo every 2 minute for changes
       pollSCM('*/2 * * * *')
   }
}