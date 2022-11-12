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
        echo "This is testing Stage"
        cat bugfix.txt
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
