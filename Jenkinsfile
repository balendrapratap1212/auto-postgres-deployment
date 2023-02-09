pipeline {

  agent any
  stages {
    stage('Run Script') {
      steps {
                script {

                    echo "Balendra"
                    sh "python3 --version"
                    sh 'pip install pyodbc'
                    sh './job.sh'
                    

                    }
                }
    }
  }
  }
