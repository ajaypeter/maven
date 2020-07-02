node{
	    stage('SCM Checkout'){
	      git ' https://github.com/ajaypeter/maven.git '
	     }
	     stage('Compile-Package'){
	      sh 'mvn -Dtest=GooglePage test -DfailIfNoTests=false'
	     }
	}
