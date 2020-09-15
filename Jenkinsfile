pipeline{
    agent any
    stages{
        stage('Upload to AWS') {
              steps {
                  sh 'echo "Hello World"'
                  sh ''''
                      echo "Multiline Shell Steps Works too"
                      ls -lah
                  '''
              }
        }
    }
}
