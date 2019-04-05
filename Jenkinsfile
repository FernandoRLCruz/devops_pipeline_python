node {
    stage 'build'
        node() {
            sh 'whoami'
            sh 'pwd'
            sh 'ls -al'
            sh 'git clone https://github.com/FernandoRLCruz/devops_pipeline_python.git'
            sh 'pwd'
            sh 'ls -al'
            sh 'pip3 install -r requirements.txt'      
        }
    stage'test'
        node() {
            sh 'python3 test.py'
        }
}
