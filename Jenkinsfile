pipeline { 
    agent any  
    stages { 
        stage('sample1') {
          steps {
            echo 'name'
          }
        }
        stage('sample 2') { 
            steps { 
               echo 'enrollment-no' 
               bat 'python vansh.py'
              //bat 'mvn package'
            }
        }
   
}
    }
