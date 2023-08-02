node{
    stage('checking test'){
        echo 'hello world'
    }
    stage('email'){
        emailext body: 'hiiii hello', subject: 'hiiii hello', to: 'graviteja9866@gmail.com'
    }
    stage('repo cloning'){
        git branch: 'main', url: 'https://github.com/CT-RaviTeja66/test55.git'
    }
}
