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
            sh 'python3 devops_pipeline_python/app.py'
            sh 'python3 devops_pipeline_python/test.py'
        }
}
