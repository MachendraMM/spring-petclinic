pipeline{

    agent any
    tools{
        maven 'maven'
    }



stages{
    //specifyvarious stages with in stage

    //stage1 .Build
    stage('Build maven project'){
        steps{
            sh 'mvn clean install package'
        }
    }
}
   // stage2 :Testing
    stage('Test'){
        steps {
            echo 'testing......'
        }
    }
}

