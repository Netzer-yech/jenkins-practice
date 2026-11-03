pipeline {
    agent any
    triggers {
        pollSCM('* * * * *')   // check the repo every ~5 minutes
    stages {
        stage('Run File') {
            steps {
                sh ''' 
		    python3 print_name.py                
                   '''
            }
        }}}
