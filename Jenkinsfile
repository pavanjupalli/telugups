pipeline{
agent any 
stages{
stage('clean'){
withMaven('apache-maven-3.6.3'){
bat 'mvn clean'
}
stage('compile'){
bat 'mvn clean compile'
}
stage('test'){
bat 'mvn clean test'
}
stage('install'){
bat 'mvn clean install'
}

}
}
}
