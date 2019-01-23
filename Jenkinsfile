def version = ''
def props = ''
def branchName = env.BRANCH_NAME //make lowercase because startsWith is case sensitive
def buildNum = ''
echo "Branch Name = ${branchName}"

node('master'){
 cleanWs notFailBuild: true
	props = readYaml file: 'project.yaml'
	def groupId= "${pom.groupId}"
	echo "GroupID" "${pom.groupId}",
	stage('Checkout'){

          checkout scm
         }
       

	
  
}
