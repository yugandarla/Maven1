def version = ''
def props = ''
def branchName = env.BRANCH_NAME //make lowercase because startsWith is case sensitive
def buildNum = ''
echo "Branch Name = ${branchName}"
def pom = readMavenPom file: 'pom.xml'
node('master'){
 cleanWs notFailBuild: true
	//props = readYaml file: 'project.yaml'
	//def pom = readMavenPom file: 'pom.xml'
	
	
	stage('Checkout'){

          checkout scm
         }
       

	
  
}
