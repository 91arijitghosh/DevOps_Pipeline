pipeline{
  
  agent any
  
  stages{
    stage('Build')
    {
      steps{
        echo "This is building Stage"
      }
    }  
    stage('Test')
    {
      steps{
        sh'''#!/bin/bash
        echo "This is testing Stage"
        cat bugfix.txt  
        '''
      }
    }  
    stage('Deploy')
    {
      steps{
        echo "This is deployment Stage"
      }
    }  
  }
}
