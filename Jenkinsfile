// pipeline {
//     agent any
//         stages {
//             stage('TEST1') {
//                 steps {
//                 echo 'Test1'
//             }
//         }
//             stage('TEST2') {
//                 steps {
//                 echo 'Test2'
//                 build job: 'roboshop-ansible', parameters: [string(name: 'COMPONENT', value: 'frontend')]
//                 emailext body: 'teset', subject: 'teste', to: 'vamsi@local.com'
//             }
//         }
//     }
//     post {
//         always
//         {
//         echo "Hello"
//         }
//         failure
//         {
//         echo "Failed State"
//         }
//         cleanup
//         {
//         echo "Common Steps"
//         }
//     }
//   }


// pipeline {
// agent any
//
// environment {
// SAMPLE_URL="google.com"
// }
//    parameters {
//         string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
//
//         text(name: 'BIOGRAPHY', defaultValue: '', description: 'Enter some information about the person')
//
//         booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')
//
//         choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
//
//         password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter a password')
//     }
//
//     triggers { pollSCM('* * * * *') }
//
// stages
// {
//
//     stage('One')
//     {
//      steps
//      {
//      sh "echo URL = ${SAMPLE_URL}"
//      echo SAMPLE_URL
//      echo PERSON
//      }
//     }
// }
// }


pipeline{
agent any
stages{
    stage('Maven Version'){
    steps {
        sh 'mvn version'
    }
    }

}


}