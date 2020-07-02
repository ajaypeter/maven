node{
	    stage('SCM Checkout'){
	      git ' https://github.com/ajaypeter/maven.git '
	     }
	     stage('Compile-Package'){
	      echo 'mvn -Dtest=GooglePage test -DfailIfNoTests=false'
	     }
	}
