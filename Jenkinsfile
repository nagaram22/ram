pipeline {
   agent any
   parameters {
       booleanParam(defaultValue: true, description: '', name: 'Check for True')
       string(defaultValue: "MARVEL", description: '', name: 'Enter any Name')
       choice(choices: 'rohit\ndhoni\nyuvi\nbaba', description: '', name: 'Select a player')
   }

   stages {
       stage("foo") {
           steps {
               echo "flag: ${params.userFlagT}"
           }
       }
   }
}
