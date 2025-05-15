pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Stage 1: Build the code using Maven or npm'
      }
    }

    stage('Unit and Integration Tests') {
      steps {
        echo 'Stage 2: Run unit tests (e.g., JUnit, Mocha)'
      }
    }

    stage('Code Analysis') {
      steps {
        echo 'Stage 3: Perform static code analysis (e.g., SonarQube or ESLint)'
      }
    }

    stage('Security Scan') {
      steps {
        echo 'Stage 4: Run security scan (e.g., Snyk or OWASP Dependency-Check)'
      }
    }

    stage('Deploy to Staging') {
      steps {
        echo 'Stage 5: Deploy the app to a staging environment (e.g., AWS EC2)'
      }
    }

    stage('Integration Tests on Staging') {
      steps {
        echo 'Stage 6: Run integration tests in staging (e.g., Postman CLI or Selenium)'
      }
    }

    stage('Deploy to Production') {
      steps {
        echo 'Stage 7: Deploy the app to production (e.g., EC2 or Kubernetes)'
      }
    }
  }
}
