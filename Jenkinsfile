def workspace;
node
{
    stage('checkout')
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/mitreid-connect/simple-web-app.git']]])
    workspace =pwd()    
}
stage('static code analysis')
{
    echo "static code analysis"
}
stage('build the code')
{
    echo "build the code"
}
stage("deploy the code")
{
    echo "deploying the code"
}
