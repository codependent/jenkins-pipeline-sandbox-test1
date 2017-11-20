pipeline {
  agent any
  stages {
	stage ('SCM') {
	  script{
	    def scmUrl = scm.getUserRemoteConfigs()[0].getUrl()
	  }
	}
  }
}