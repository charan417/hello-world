node {
    stage('Getting the code from git repository'){
        git 'https://github.com/charan417/hello-world.git'
    }
    stage('building the code using maven'){
        sh label: '', script: 'mvn clean package'
    }
    
}
