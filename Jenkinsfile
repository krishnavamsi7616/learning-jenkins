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


pipeline {
agent any

environment {
SAMPLE_URL="google.com"
}

stages
{

    stage('One')
    {
     steps
     {
     sh "echo URL = ${SAMPLE_URL}"
     echo SAMPLE_URL
     }
    }
}
}