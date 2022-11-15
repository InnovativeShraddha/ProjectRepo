Pipeline 
{ 
tools{
        jdk 'myjava'
        maven 'mymaven'
    }
  
  agent Jenkins_slave 
 stages{ 
 
      stage('Package'){
		  
              steps{
		  
                  sh 'mvn package'
              }
          }
	     
  
}
