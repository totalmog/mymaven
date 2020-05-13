def workspace;
node
{stage('checkout')
{
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '1bcf0b2b-aa56-430c-9187-4b3bf431b6ec', url: 'https://github.com/totalmog/dev.git']]])
    worksapce =pwd()
}
    stage ('static code analysis')
    {
        echo"static code analysis"
    }
    stage ('Build')
    {
        echo"Build the code"
    }
    stage ('Unit testing')
    {
        echo"Unit testing"
    }
    stage ('Delivery')
    {
        echo "Deliver the code"
    }
    
}
