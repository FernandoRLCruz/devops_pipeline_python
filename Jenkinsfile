node {
    stage 'build'
        node() {
            sh 'whoami'
            sh 'pwd'
            sh 'ls -al'
            sh 'pwd'
            sh 'ls -al'
            sh 'pip3 install -r devops_pipeline_python/requirements.txt'      
        }
    stage'test'
        node() {
            sh 'python3 test.py'
        }
}
