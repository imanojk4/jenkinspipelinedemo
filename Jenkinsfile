pipeline{
    tools{
        jdk 'my java'
        maven 'mymvn'
    }
    
    agent any
    
    stages{
        stage('clone repo')
        {
             steps{
                    git 'https://github.com/Sonal0409/DevOpsCodeDemo.git'
                  }
        }
        stage('compile')
        {
             steps{
                    sh 'mvn compile'
                    }
        }
    }
}
