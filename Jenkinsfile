def version = ''
def props = ''
def branchName = env.BRANCH_NAME //make lowercase because startsWith is case sensitive
def buildNum = ''
echo "Branch Name = ${branchName}"

node('master'){
 cleanWs notFailBuild: false
	//props = readYaml file: 'project.yaml'
	//def pom = readMavenPom file: 'pom.xml'
	
	
	stage('Checkout'){

          //checkout scm
         }
       
stage('Example') {
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute other branch:' env.BRANCH_NAME
        }
    }
	
  
}
