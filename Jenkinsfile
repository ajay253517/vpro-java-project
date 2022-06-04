pipeline {
agent { node { label 'docker' } } 
    
stages {
stage("Checkout") {
steps {
git  branch: 'master', url: 'https://github.com/ajay253517/vpro-java-project.git'
}
}
stage("check-mvn") {
steps {
sh "mvn --version"
}
}
}
}