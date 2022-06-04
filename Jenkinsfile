pipeline {
agent { node { label 'docker' } } 
    
stages {
stage("Checkout") {
steps {
git  branch: 'main', url: 'https://github.com/ajay253517/vpro-java-project.git'
}
}