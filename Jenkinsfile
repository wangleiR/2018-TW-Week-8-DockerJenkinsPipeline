node {
stage('CheckOut'){
checkout scm
echo 'Check Out Stage!'
sh './gradlew clean'
}
stage('Build'){
echo 'Build Stage!'
sh './gradlew build'
}
stage('Test'){
echo 'Test Stage'
sh './gradlew test'
}
}
