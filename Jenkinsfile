node {
    stage 'build'
        node() {
            sh 'whoami'
            sh 'pwd'
            sh 'pip3 install -r requirements.txt'      
        }
    stage'test'
        node() {
            sh 'python3 test.py'
        }
}
