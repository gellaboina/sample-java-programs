pipeline {
  agent any
  stages {
    stage ('git repo https://github.com/gellaboina/sample-java-programs.git') {
      step {
        echo 'hello'
      }
      stage ('build') {
        step {
          echo 'mana'
        }
          stage ('test') {
            step {
              echo 'goo'
            }
        }
      }
    }
  }
      
