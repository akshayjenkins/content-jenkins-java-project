pipeline {
 
 agent any
 stages {
 stage('build') {
 steps {
 echo 'Bulding'
 }
 }
 
 stage('run') {
 steps {
echo 'tesing'
 }
 }
  stage('Deploy') {
 steps {
echo 'Deploying'
 }
  }
 
 }
post {
 success {
 archiveArtifacts artifacts: '*', fingerprint: true
 }
 }
  
}
