node {
      stage 'build'
        node() {
              sh 'pip install -r requirements.txt'      
        }
    stage'test'
        node() {
        sh 'python test.py'
      }
}