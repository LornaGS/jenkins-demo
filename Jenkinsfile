pipeline {

    // jenkins pipeline in groovy

    agent any

    stages {
        stage('Make folders and files'){

            steps {
                //what we want jenkins to do
                bat 'mkdir testingPipeline '// starts batch command - making new directory 
               
                    // rather than having multiple bat commands this does the same thing bat '''  then commands then '''

                bat '''
    

                '''

                //and can use any language

            }

        }
        stage('View'){

            steps {
                //

                  bat '''
            dir
            type testingPipeline\text.txt

                '''

            }

        }
        stage('Run'){

            steps {
                //
                bat 'script.bat'

            }

        }

    }

