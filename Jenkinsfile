node {
    stage 'build'
        node() {
            sh 'whoami'
            sh 'pip install -r requirements.txt'      
        }
    stage'test'
        node() {
            sh 'python test.py'
        }
}
