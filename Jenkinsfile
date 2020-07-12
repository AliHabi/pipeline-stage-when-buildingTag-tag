pipeline {
	agent any
	
	stages {
	    stages('Build'){
	    	when {
			buildingTag()
		}
            
	    steps {
	            echo "Hello World building tag"
	      }
	   } 
	}

}
