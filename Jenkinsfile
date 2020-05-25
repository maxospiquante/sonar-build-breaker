node ('master') {
          
          stage('Checkout') {
	    checkout scm
	}
          
         stage ('Build') {
           
                sh 'mvn -U clean package  ' 
            
        }
 
}
