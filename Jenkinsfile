pipeline {
  agent { docker { image 'python:3.8' } }
  stages {
    stage('build') {
      steps {
			sh 'python -m venv .venv'
			sh '''
				. .venv/bin/activate
				pip install -r requirements.txt
			
			'''
      
      }
    }

    
    }
  }





