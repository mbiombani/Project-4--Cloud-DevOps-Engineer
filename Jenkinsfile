pipeline {
     agent any
     stages {
         stage('Upload to AWS') {
             steps {
                 sh 'echo "Hello World"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
               
withAWS(credentials:'IDofAwsCredentials') {
    // do something
}
s3Upload ( fichier : ' file.txt ' , bucket : ' my-bucket ' , path : ' path / to / target / file.txt ' )
s3Upload ( fichier : ' someFolder ' , bucket : ' my-bucket ' , path : ' path / to / targetFolder / ' )
             }
         }
       }
    }
