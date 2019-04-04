node {
    stage 'build'
        node() {
              sh 'sudo apt-get install python3-pip'
              sh 'sudo apt-get update'
              sh 'pip install -r requirements.txt'      
        }
    stage'test'
        node() {
            sh 'python test.py'
        }
}